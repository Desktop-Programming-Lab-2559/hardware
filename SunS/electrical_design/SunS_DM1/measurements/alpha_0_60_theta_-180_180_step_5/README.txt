Pomiar dla Alpha od 0deg do 60deg, Theta od -180deg do +180deg, krok 5 deg.

Kolumny w pliku raw_log.csv:
Alpha - warto�� k�ta Alpha,
Theta - warto�� k�ta Theta,
Device - nazwa czujnika (http://www.farnell.com/datasheets/1813319.pdf),
Sensor0 - Numer sensora
Visible0 - warto�� odczytana przez czujnik z kana�u widzialnego �wiat�a,
IR0 - warto�� odczytana przez czujnik z kana�u bliskiej podczerwieni,
... i tak na zmian� SensorX, VisibleX, IRX do 11 (od 0 do 11, to razem 12 czujnik�w).
Na ko�cu s� 4 temperatury, ale na razie s� fejkowe (p�niej b�d� dzia�a�y).