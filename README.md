# Rpa-ResmiGazete
Robot ilk olarak resmi gazete sayfasını açıyor. 
Gelen ekrandaki başlık kısmını alıyor. Alınan başlığı regex kullanarak tarih kısmını ayırdım.
Bugünün tarihi ile alınan tarihi karşılaştırdım. Aynıysa içeriği aldım ve mail olarak ilettim.
Son mükerrer sayfasındaki başlık kısmındaki tarih ile dünün tarihi aynı ise o içeriğide alıyor ve önceki mükerrerleri de kontrol ediyor eğer tarihler aynı ise içerik alınır. Alınan tüm içerikler tek bir mail ile iletiliyor.
