
# Vitajte v elektronickej učebnici!

Táto učebnica je venovaná počítačovým sieťam.

## Hello World! test:

Ak vidíte tento text, Zensical funguje správne.


Otestujeme prehrávanie videa uloženého na Nextcloude.

## 1. Natívne video v Zensicale


![type:video](https://cloud.e-siete.milpet.eu/s/eFb3yenwcA23M7c/download)

## 2. HTML5 video

<video controls preload="metadata" playsinline
       style="width: 100%; height: auto;">
    <source
        src="https://cloud.e-siete.milpet.eu/s/eFb3yenwcA23M7c/download"
        type="video/mp4">
    Váš prehliadač nepodporuje prehrávanie videa.
</video>


## Test Obrazku

## 1. Obrázok z Nextcloudu cez Markdown

![Topológia siete](https://cloud.e-siete.milpet.eu/s/Bcm2qWiRZBFRK3P/download)

## 2. Obrázok z Nextcloudu cez HTML

<img
  src="https://cloud.e-siete.milpet.eu/s/Bcm2qWiRZBFRK3P/download"
  alt="Topológia siete"
  style="width: 100%; max-width: 700px;"
  loading="lazy"
>


## Ako sa učí sieťový prepínač?

Sieťový prepínač sa učí MAC adresy
z prichádzajúcich ethernetových rámcov.

??? question "Z ktorej MAC adresy sa prepínač učí?"

    Prepínač si zapamätáva **zdrojovú MAC adresu**
    rámca a port, na ktorom rámec prijal.

??? question "Čo sa stane, ak nepozná cieľovú MAC adresu?"

    Rámec odošle cez všetky ostatné porty
    v príslušnej VLAN, okrem portu,
    na ktorom ho prijal.

!!! success "Hotovo!"

    Naša prvá elektronická učebnica funguje!
