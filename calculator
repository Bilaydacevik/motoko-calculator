actor hesap_makinesi {
  var hucre: Int = 0; // Başlangıç değeri atanmalı

  // Toplama
  public func toplama(s: Int): async Int {
    hucre += s; // Değer ekle
    return hucre; // Sonucu döndür
  };

  // Çıkarma
  public func cikarma(s: Int): async Int {
    hucre -= s; // Değer çıkar
    return hucre; // Sonucu döndür
  };

  // Çarpma
  public func carpma(s: Int): async Int {
    hucre *= s; // Çarpma işlemi
    return hucre; // Sonucu döndür
  };

  // Bölme
  public func bolme(s: Int): async ?Int {
    if (s == 0) {
      return null; // Sıfıra bölme hatası
    } else {
      hucre /= s; // Bölme işlemi
      return ?hucre; // Sonucu opsiyonel döndür
    };
  };

  // Temizle
  public func temizle(): async () {
    hucre := 0; // Hücre sıfırlama
  };
};
