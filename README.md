# v-cutkitleendeksi
package patika;
import java.util.Scanner;
public class vücutkitleendeksi {

	public static void main(String[] args) {
		double boy , kilo , vücutI;
		Scanner inp = new Scanner(System.in);
		System.out.println("Kilonuzu giriniz:");
		kilo = inp.nextDouble();
		System.out.println("Boyunuzu metre cinsinden giriniz:");
		boy = inp.nextDouble();
		vücutI = kilo / (boy * boy );
		System.out.println("Vücut kitle endeksiniz :" + vücutI);
		
	

	}

}
