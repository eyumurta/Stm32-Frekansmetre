# Stm32-Frekansmetre
Stm32 ile dış kesme kullanarak frekans ölçme uygulaması
Bu örnek uygulama PB4 dış kesmesini kullanarak frekans ölçümü yapmaktadır.
İlk yükselen kenar algılandığına Timer1'in ilk değeri okunur.
İkinci yükselen kenar geldiğinde Timer1 ikinci kez okunur.
Okunan iki değerin farkı alınır.Frekansa çevrilip 1 milyon ile çarpılır.
Bulduğunuz hataları bildirirseniz memnun olurum.
Ölçülen frekans OLED ekrana yazdırılır.
