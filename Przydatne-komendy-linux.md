# Przydatne komendy w systemie Linux, często występujące w zadaniach egzaminacyjnych

### Komenda na wygasanie hasła

```
sudo passwd -x <ilość dni> <użytkownik>
```

### Komenda na dodanie grupy

```
sudo addgroup <nazwa grupy>
```

### Komenda na dodanie użytkownika do grupy

```
sudo adduser <użytkownik> <nazwa grupy>
```

### Komenda na przejęcie pliku przez innego użytkownika

```
sudo chown <użytkownik> <nazwa pliku>
```

### Zmiana domyslnego systemu i timeout w Grubie

```
sudo nano /etc/default/grub
GRUB_DEFAULT=1
GRUB_TIMEOUT=10
sudo update-grub
```
