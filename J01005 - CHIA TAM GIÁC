//Note !

//- Diện tích tam giác cân là 1/2 * b * h = h/2.

//- Chia tam giác ra thành n tam giác bé có nghĩa là
//tất cả tam giác bé đồng dạng vs tam giác gốc ban đầu
//và đồng dạng vs nhau.

//- Diện tích của tam giác thứ i trong n tam giác con là Sn = i/n S = i/n * 1/2 * h = h*i/2n.

//- Ta có tam giác bé đồng dạng với tam giác to nên tỉ lệ đường cao và cạnh đáy của 2 tam giác là
//hi/H = bi/B ( hi bi là đường cao cạnh đáy tam giác bé thứ i ) <=> hi/H = bi ( B = 1 ).

//- Suy ra diện tích tam giác bé thứ i là: (1/2) * hi/H * hi = hi^2/2H.

//- Suy ra hi^2/2H = H*i/2n.

//- Suy ra hi = H * sqrt(i/n).

//- Cẩn thận với kiểu float và double bởi vì float chỉ có thể lưu trữ 6-7 số sau dấu phẩy 
// và có thể làm tròn sai.

import java.util.Scanner;

public class J01005_CHIA_TAM_GIÁC {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        int t = scanner.nextInt();

        while ( t > 0 ) {

            int n = scanner.nextInt();
            int h = scanner.nextInt();

            for ( int i = 1; i < n; i++ ) {
                double hi = (double)i/(double) n;
                double ans = (double) h * (double) Math.sqrt(hi);
                System.out.printf("%.6f ", ans);
            }

            System.out.println("");

            --t;

        }

    }

}
