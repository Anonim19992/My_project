____
Решил для себя сделать GUI для ClamAV (для контекстного меню).
# 
Почему не CLAMTK (GUI GTK обертка над clamav)? 
#
Много нюансов.
# 
Начиная с того, что CLAMTK не видит явные вирусы, которые ClamAV видит (EICAR тест), заканчивая многими другими нюансами.
____
В планах:
##
1) Сделать определение файлового менеджера для универсальности данного скрипта (nemo/nautilus/dolphin и т.д.)
##
2) Сделать вывод в zenity количество провереных / проверяемых файлов. (Готово)
##
3) Сделать определение языков системы. 
