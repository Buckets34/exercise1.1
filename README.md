class Bicycle{
	private String ownerName;
	private String tagno;

	public Bicycle (){
		ownerName="";
		tagno="";
	}
	public String getownerName(){
		return ownerName;
	}
	public void setownerName(String name){
		ownerName = name;
	}
	public String getTagNo(){
		return tagno;
	}
	public void  setTagNo(String tag){
		tagno = tag;


	}
	}
class BicycleRegistration{
	public static void main(String[] agrs){

		Bicycle bike;
		Bicycle bike1,bike2,tagno1,tagno2;
		String owner1,owner2;
		String Tagnum1,Tagnum2;

		bike1=new Bicycle();
		bike1.setownerName("Buckets");

		bike2=new Bicycle();
		bike2.setownerName("Hangad");

		tagno1 =new Bicycle();
		tagno1.setTagNo("1288-879");
		
		tagno2=new Bicycle();
		tagno2.setTagNo("3433-2938");

		owner1=bike1.getownerName();
		owner2=bike2.getownerName();
		Tagnum1=tagno1.getTagNo();
		Tagnum2=tagno2.getTagNo();
		System.out.println("\t"+ owner1 +" owns a bicycle with a tag Number: "+ Tagnum1);
		System.out.println("\t"+ owner2 +" also owns a bicycle with a tag Number:"+ Tagnum2);




	}
	}
