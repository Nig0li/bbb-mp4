# bbb-mp4
BigBlueButton Record Process

# �������

## extractCursorEvents
    php extractCursorEvents.php --src=events.xml --dst=events.new.xml > cursor.events

��������� ��������� ������� �� ����� events.xml. ������� ����� ���� events.new.xml ��� ���. ��������� �� �������
��������� � stdout ��� CSV "timestamp,x,y"

## generateCursorPng
    php generateCursorPng.php --src=./cursor.events --dst=./cursor/ --width=1280 --height=720 --diameter=10

������� �� ���� ����� ������� ������� � ������� CSV ������������������ ������ � ������� PNG � ������������ �������.
�������� �����, ���� ����� ��������� ������������������ �����������, �� ������ � ������ � ������ ����� �������

# ���� (��� �� ������� ������)
## NotesWindow
## BroadcastWindow
## PresentationWindow
���� ������ �������
## VideoDock
## ChatWindow
���� ����
## UsersWindow
������ �������������
## ViewersWindow
## ListenersWindow