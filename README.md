<h1 align="center">Stucdio Yazılım</h1>
<p align="center">Mobil & backend geliştirme — Flutter · PHP · Go</p>

---

Çalışmalarımın çoğu özel (private) repolarda yürüyor; burada paylaşabildiğim somut bir şey,
Flutter framework'üne (Google) giden bir katkı:

**[flutter/flutter#190172](https://github.com/flutter/flutter/pull/190172)** — build/scheduler
pipeline'ında, `State.dispose()` sırasında oluşan nadir bir race condition'ı kök nedenine kadar
izleyip düzelttim.

Ağırlıklı olarak Flutter ile mobil uygulama, PHP/Go ile backend ve gerçek zamanlı sistemler
üzerine çalışıyorum.
