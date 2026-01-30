# Single Node k3s kurulum

```bash
Sunucu IP: IP_ADRESINIZ (Örnek: 192.168.1.10)
Ingress IP: IP_ADRESINIZ+1 (Örnek: 192.168.1.11)
```

## Gereksinimler

- Custom Servis: Basit bir nginx servisi servisi oluşturup http://INGRESS_IP  tarayıcadan eriştiğimizde "ER&KUT DevOps - We Love Kubernetes" yazsın.
- HELM kullanılacak.
- Repoları fork edip kendi forklarını kullanarak, kabaca dökümante edilecek. Values dosyaları eklenecek.

## Tamamlanması gereken görevler

- [ ] Ubuntu 24 server kurulumu
- [ ] k3s kurulumu
- [ ] MetalLB ile ipaddresspool oluşturulması
- [ ] Ingress kurulumu
- [ ] Custom Servis docker imajı oluştur.
- [ ] Custom Servis i kubernetes deploy et.
