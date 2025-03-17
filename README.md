# Komunikace STM32 a Matlab

Tento projekt umožňuje efektivní propojení mikrokontroléru STM32 s MATLABem pro sběr, analýzu a vizualizaci dat. Podporuje metod přenosu přes USB (virtual Com Port).

# Cílové skupiny

## 1. Vývojáři embedded systémů STM32

Použití: Testování a ladění firmwaru pomocí MATLABu, rychlá vizualizace a analýza dat ze senzorů.
Důvod použití: Potřebují rychlý a spolehlivý přenos dat mezi STM32 a MATLABem pro efektivní vývoj a ladění.

## 2. Výzkumníci a akademici

Použití: Propojení MATLABu se STM32 pro experimenty v reálném čase, sběr dat ze senzorů a jejich analýza.
Důvod použití: MATLAB je pro ně standardním nástrojem, umožňuje snadný přechod od simulací k reálným experimentům.

# Dostupné manuály

## 1. Technická příručka pro vývojáře

Nastavení komunikace mezi STM32 a MATLABem (USB virtual com port).

Ukázkový kód firmwaru pro STM32 v C/C++.

Skripty MATLABu pro příjem a zpracování dat.

Řešení běžných problémů (nesprávná baud rate, chybějící ovladače).

Specifikace přenosu (rychlost, formát dat, limity).

## 2. Uživatelská příručka pro akademiky

Krok za krokem: propojení STM32 s MATLABem.

Ukázkové experimenty (např. sběr dat z nějakých dalších přístroje).

Rozšíření pro další MATLAB toolboxy (Signal Processing, Control Systems).

Vysvětlení základních pojmů komunikace.

## 3. Manuál pro automatizaci testů

Nastavení STM32 pro kontinuální odesílání testovacích dat.

MATLAB skripty pro automatizované logování a analýzu.

Přizpůsobení komunikace různým testovacím zařízením.

Měření latence a propustnosti přenosu.

# Požadavky

STM32 mikrokontrolér (doporučeno STM32F732)

MATLAB s podporou komunikace přes sériový port

Kompilátor pro C/C++ (STM32CubeIDE)

Instalace a spuštění

Nastavte STM32 virtual com port (USB), nastavení časovače.

Nahrajte odpovídající firmware do STM32.

Spusťte MATLAB a načtěte skripty pro příjem a zpracování dat.

Ověřte přenos a analyzujte výsledky.
