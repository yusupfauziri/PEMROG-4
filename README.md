# PEMROG-4


package kendaraan ;
public class Kendaraan {
private int tanggalProduksi;    
    
public Kendaraan (){
}

protected void bergerak () {
        System.out.println("kendaraan dapat bergerak..");
}
public void mengerem () {
    System.out.println("kendaraan dapat mengerem..");
}
}

package kendaraan;

/**
 *
 * @author STUDENT
 */
public class pesawat extends Kendaraan {
public pesawat (){
    super();
}

protected void terbang () {
        System.out.println("pesawat dapat terbang ..");
}
}

    package kendaraan;

/**
 *
 * @author STUDENT
 */
public class NewMain {

    
    public static void main(String[] args) {
        Kendaraan A=new Kendaraan ();
        A.bergerak();
        A.mengerem();
        
       mobil B=new mobil ();
       B.berjalanMundur();
       B.bergerak();
       B.mengerem();
       
       pesawat C=new pesawat ();
       C.terbang();
       C.bergerak();
       C.mengerem();
    }
}

