import java.text.SimpleDateFormat;
import java.util.Date;

public class Main {
  public static void main(String[] args) throws Exception {
    SimpleDateFormat inputFormat = new SimpleDateFormat("yyyy-MM-dd");
    SimpleDateFormat outputFormat = new SimpleDateFormat("MM-dd-yyyy");
    Date date = inputFormat.parse("2022-01-01");
    String output = outputFormat.format(date);
    System.out.println(output);  // Outputs: "01-01-2022"
  }
}
