# shell-assessment-poojayadav


STEPS THAT I HAVE PERFORMED ON MY TERMINAL:-
poojayadav@Poojas-MacBook-Pro ~ % mkdir my_folder
poojayadav@Poojas-MacBook-Pro ~ % cd my_folder 
poojayadav@Poojas-MacBook-Pro my_folder % echo "This is the first file." > my_file.txt

poojayadav@Poojas-MacBook-Pro my_folder % echo "This is the second file." > another_file.txt

poojayadav@Poojas-MacBook-Pro my_folder % cat another_file.txt >> my_file.txt

poojayadav@Poojas-MacBook-Pro my_folder % cat my_file.txt

This is the first file.
This is the second file.
poojayadav@Poojas-MacBook-Pro my_folder % ls -l

total 16
-rw-r--r--  1 poojayadav  staff  25 25 Jul 15:12 another_file.txt
-rw-r--r--  1 poojayadav  staff  49 25 Jul 15:12 my_file.txt
poojayadav@Poojas-MacBook-Pro my_folder % touch file{1..20}.txt

poojayadav@Poojas-MacBook-Pro my_folder % for i in {1..5}; do mv "file$i.txt" "file$i.yml"; done

poojayadav@Poojas-MacBook-Pro my_folder % ls -lt | head -n 5

total 16
-rw-r--r--  1 poojayadav  staff   0 25 Jul 15:14 file20.txt
-rw-r--r--  1 poojayadav  staff   0 25 Jul 15:14 file19.txt
-rw-r--r--  1 poojayadav  staff   0 25 Jul 15:14 file18.txt
-rw-r--r--  1 poojayadav  staff   0 25 Jul 15:14 file17.txt

->After this I pushed it on git.
