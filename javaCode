import java.util.*;
// Ömer Temel
public class Main {

    public static void main(String[] args) {
        // Türkiye Covid-19 ile mücadele ile başlatmış olduğu şehirler arası en düşük vaka sayısı yarışması.
        String city_Name = "";
        int caseCount = 0;
        boolean first = false;
        int minCase = 0;
        String minCity = "";
        Scanner scanner = new Scanner(System.in);

        // Şehir isimlerinin ve vaka sayılarının girilmesi için döngü
        // (81 il olduğu için,  81 döngü olması gerekir fakat örnek program olduğu için 3 döngü yeterlidir.)
        for (int i = 1; i <= 3; i++)
        {
            System.out.print("Şehir ismi: ");
            city_Name = scanner.next();
            System.out.print("Vaka sayısı: ");
            caseCount = scanner.nextInt();

            if (first == false)
            {
                minCase =caseCount;
                minCity = city_Name;
                first = true;
            }
            else{
                if (caseCount < minCase){
                    minCase = caseCount;
                    minCity = city_Name;
                }
            }
        }

        System.out.println("En düşük vaka sayısına sahip \n Şehir: "+minCity+"\n Vaka sayısı: "+minCase);

    }

}
