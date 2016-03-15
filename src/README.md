src
===  
Masukkan file **.java** saja di folder ini, hapus pendefinisian package.


public class cetakanKue {
    public static void main(String[] args) {
        //object created
        cetakan k1=new cetakan();
        cetakan k2 =new cetakan("Onde-onde",1000);
        
        //message displayed
        k1.displayMessage(k2);
        
        
        
    }
    
}
