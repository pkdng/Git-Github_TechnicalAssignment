1.  Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu
![2021-09-21](https://user-images.githubusercontent.com/82448171/134212149-39e8e7c3-5115-4621-bcd6-6540b06ff1cd.png)

2.  Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.
    **git clone https://github.com/pkdng/tech4impact-students-bio.git**
    
    
3.  Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.
    **git branch putri-fajriana**
    
    
4.  Checkout ke dalam branch tersebut yang telah kamu buat
    **git checkout putri-fajriana**


5.  Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md
    **touch putrifajriana.md**


6.  Isi file tersebut davidwinalda.md dengan konten di bawah ini:
    Nama Lengkap: David Winalda
    Umur: 27
    Pesan yang ingin disampaikan: Semangat untuk kamu yang disana sedang berjuang
    ![Capture](https://user-images.githubusercontent.com/82448171/134213306-b7743016-dd9b-4a9e-822b-7968dd502329.PNG)
    
7.  Masukkan file .md tersebut ke dalam staging area
    **git add putrifajriana.md**


8.  Commit dengan memberikan pesan nama file .md kamu
    **git commit -m "putrifajriana.md"**


9.  Merge branch yang telah kamu buat ke dalam branch master
    **git checkout master**
    
    **git merge putri-fajriana**


10. Push ke dalam branch master
    **git push -u origin master**
    

11. Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya.
    ![2021-09-21 (6)](https://user-images.githubusercontent.com/82448171/134213825-32504d54-4be7-4317-86cb-946f86d6c9ac.png)
    
