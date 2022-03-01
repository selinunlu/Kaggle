# EnerjiSA Enerji Veri Maratonu | TRAI x Coderspace Yarışması
## Production Estimation of Solar Power Plants

Bu projedeki amaç, lisanssız güneş enerjisi santrallerinin üretim miktarlarını saatlik bazda tahmin edilmesidir. Öncelikle Veri Keşfi yapılacaktır. Başarı metriği RMSE(Root Mean Square Error) olarak belirlenmiştir.

Tahmin edilmesi istenen tarih aralığı: `01.12.2021 – 31.12.2021` 

Veri seti içeriği hakkındaki genel bilgiler:

- `DateTime`: Sıcaklık değişkenlerinin gözlemlendiği, üretimin yapıldığı saat aralığını tarih-saat formatında belirtir. 

- `AirTemperature`: Saat aralığındaki hava sıcaklığını **Celsius** biriminde belirtir.

- `ComfortTemperature`: Saat aralığındaki hissedilen hava sıcaklığını **Celsius** biriminde belirtir.

- `RelativeHumidity`: Saat aralığındaki nem oranını belirtir.

- `WindSpeed`: Saat aralığındaki rüzgar hızını km/s biriminde belirtir.

- `WindDirection`: Saat aralığındaki rüzgar yönünü belirtir.

- `WWCode`: Saat aralığındaki hava durumu kodunu belirtir.

- `EffectiveCloudCover`: Saat aralığındaki bulutluluk oranını sekizlik ölçü birimi cinsinden belirtir.

- `Generation`: İlgili saat aralığında yapılan toplam üretimi MWh biriminde belirtir.
