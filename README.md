# include <stdio.h>

int main() {
    int n, i;
    float sayi, toplam = 0.0;

    printf("Kaç adet sayı gireceksiniz: ");
    scanf("%d", &n);

    // Kullanıcıdan n adet sayı alınıyor ve toplanıyor
    for (i = 1; i <= n; ++i) {
        printf("Sayı %d: ", i);
        scanf("%f", &sayi);
        toplam += sayi;
    }

    // Toplam ekrana yazdırılıyor
    printf("Girdiğiniz sayıların toplamı = %.2f\n", toplam);

    return 0;
}
