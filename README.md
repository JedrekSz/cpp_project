# 🛒 Shop Management Application

## Opis
Aplikacja desktopowa napisana w C# (WPF), symulująca prosty system sklepu.  
Pozwala na zarządzanie produktami, użytkownikami oraz operacjami zakupu.

---

## Architektura

Projekt składa się z kilku warstw:

- **DataLayer** – obsługa bazy danych (repozytoria, modele, SQL)
- **LogicLayer** – logika biznesowa (operacje na danych)
- **PresentationLayer** – interfejs użytkownika (WPF, MVVM)
- **Tests** – testy jednostkowe dla poszczególnych warstw
