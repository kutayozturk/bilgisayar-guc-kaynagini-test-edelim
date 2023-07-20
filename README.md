# Bilgisayar Güç Kaynağı Testi

![1](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/801f131f-5aa4-42e8-a0d5-007a9d40de47)

Bu yazıda, güç kaynağının veya bilgisayar gücünün nasıl test edileceğini tartışacağız. Genellikle sistem sorunlarını giderirken ve bilgisayar sorunlarını teşhis ederken, güç kaynağının veya bilgisayar gücünün test edilmesi unutulur. Sisteminizde sorun gidermeye güç kaynağından veya güç kaynağından başlarsanız, birçok sorun giderme sorunundan kurtulabilirsiniz.

Sisteminiz mavi bir ölüm ekranı gösteriyorsa veya bir sabit sürücü hatasıyla karşılaşıyorsanız veya sisteminiz açılmıyorsa, hatalı bir güç kaynağınız olabilir. Sistem donanımınızı değiştirmeden önce, güç kaynağını veya bilgisayar gücünü birkaç basit adımda test etmeyi unutmayın.

## Test Adımları
Sisteminiz açıksa kapatın ve sistemin arkasındaki güç düğmesini Off'a getirin ve güç kaynağı kablosunu prizden çıkarın.

![2](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/7718a4e1-336a-42d0-b703-cfa826a34078)

Bilgisayar kasasını açın ve kasanın içindeki diğer bileşenlere bağlı olan tüm güç kaynağı kablolarını çıkarın. Güçten bileşenlere bağlı tüm kabloları takip edin ve tüm kabloların doğru şekilde çıkarıldığından emin olun

![3](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/0112493b-02a0-41c9-adc5-e7d16d3dec3f)

Şimdi bir test cihazı oluşturmanız gerekiyor. Güç kaynağını anakarta bağlamadan açmak için yeşil pini siyah pinlerden birine bağlamanız gerekiyor. Bunun için bir tel parçası kullanabilir ya da elinizdeki ataşı U şeklinde bükebilirsiniz.

![4](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/1b60df07-3c41-4dc3-888e-e8407a45d04e)

Şimdi ana karta bağlanan 20/24 pin konektörünü bulun. Genellikle bu konektör en büyük güç kaynağı konektörüdür.

![5](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/d6132119-f46e-4fc0-bff5-63bfc5f7aa37)

Yeşil iğneyi ve siyah iğneyi bulun (genellikle iğne 15 ve 16). Yaptığınız test cihazının bir tarafını yeşil pime (sadece bir yeşil pim vardır) ve diğer tarafını siyah pime yerleştirin. Tabii ki, bunu yapmadan önce, güç kaynağının herhangi bir elektrik prizinden tamamen çıkarıldığından ve anahtarın 0'a ayarlandığından ve gücün herhangi bir bilgisayar bileşenine bağlı olmadığından emin olmalısınız.

![6](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/d0a5d7d2-cbf4-49b6-818f-15c2a07a86ef)

![7](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/2a4ac20f-2dcf-43d2-b9c5-b215a6f63b99)

Kabloyu belirtilen pinlere taktıktan sonra güç kaynağını prize takın ve anahtar düğmesini 1 konumuna getirin.

![8](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/e5dd702d-cc52-43f6-ad80-258cf3175ee0)

Güç kaynağınız sağlıklıysa, fanın sesini duymanız veya fan kanatlarının hareketini görmeniz gerekir. Güç kaynağı açılırsa, test cihazının bağlantısını kesin ve tekrar bağlayın.Güç kaynağı hala sızdırıyorsa, o zaman maalesef güç kaynağınızın yandığını ve yeni bir güç kaynağı satın almanız gerektiğini söylemeliyiz. Bu test size sadece güç kaynağınızın açılıp açılmadığını gösterir ve güç kaynağının çıkış voltajını göstermez.Bunun için aşağıdaki geçici çözümü okumalısınız.

## Çıkış Voltajı Testi

Sisteminiz çalışıyorsa ve işletim sistemi önyükleme yapabiliyorsa, güç kaynağının çıkışını kontrol etmek için yazılımı kullanmayı deneyin. SpeedFan , size güç kaynağının voltajı ve sıcaklığı hakkında bilgi gösteren ücretsiz bir programdır. Bilgisayarınız açılmıyorsa bir sonraki adıma geçin.

![9](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/86396678-aecf-476e-b9bc-721b97d7b6cf)

Bilgisayarı kapatın ve güç kaynağı anahtarını 0'a ayarlayın ve güç kaynağı kablosunu prizden çıkarın. Güç kaynağı kablolarını sistemin içindeki bileşenlerden ayırın.

![10](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/32111694-c1b5-4a15-b4fc-f5c567b4e953)

Herhangi bir elektronik mağazasından bir multimetre alabilirsiniz ve çok pahalı değildir. Güç kaynağı bağlantı noktası 20/24 konektörünü bulun. Multimetreyi DC aralığına getirin ve güç kaynağı pinlerinin voltajını sırayla ölçün. Bazı pimleri test etmek için güç kaynağını (test cihazı aracılığıyla) açmak gerekir, ancak diğer kablolar için bu gerekli değildir. İhtiyacınız olan 4 temel ölçüm aşağıdaki gibi olmalıdır:

- +3,3 VDC (paslanmaz çelik tel için)
- +5 VDC (kırmızı kablo için)
- +12 VDC (sarı kablo için)
- -12 VDC (mavi kablo için)

Voltajların +3,3, +5, +12 pinleri için +/-%5 toleransa sahip olduğundan emin olun, ancak -12 pini +/-%10 toleransa sahip olabilir. Tolerans, istenen voltaj değerinin yüzde beş daha az veya daha fazla olabileceği anlamına gelir (+/-%5 için).

Bu fişlerin bu aralığın dışında bir voltaj gösterdiğini fark ederseniz, bu güç kaynağınızın bozulduğu ve değiştirmeniz gerektiği anlamına gelir. Test sırasında, multimetrenin negatif probunu toprak (siyah) pime ve pozitif probu test etmek istediğiniz diğer pime bağlamanız gerektiğini unutmayın.

![11](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/d71c85b4-0882-4fe3-b0c1-7b838607dc3c)

Güç kaynağınızın sağlıklı olduğundan emin olduktan sonra güç kaynağınızı sisteme tekrar takıp kasanızı kapatabilirsiniz.

![12](https://github.com/kutayozturk/bilgisayar-guc-kaynagini-test-edelim/assets/94574681/0068c7e2-f85a-4051-85f9-dad566ff6d61)
