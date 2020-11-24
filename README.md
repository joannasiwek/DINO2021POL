# DINO2021POL

Zajęcia 4 - Git - instrukcja

Wymagania:

Odpowiedzi powinny mieć formę 1 pliku HTML opracowywanego przez całą grupę.
Plik powinien być estetyczny i gramatycznie poprawny.
Każda osoba opracowuję 1 komendę.

Jak to zrobić:
Każdy student klonuje repozytorium.
Student wprowadza zmiany na swojej kopii a następnie wysyła Pull request.
Pull request może zostać odrzucony np. z powodu pracowania na nieaktualnej kopii pliku lub opracowywania konendy, która została już zmerdżowana (kto pierwszy ten lepszy).
Proszę zatem wielokrotnie w ciągu tygodnia sprawdzić, czy Państwa pull requesty zostały wciągnięte.
Żeby dostać pkt za zadanie prosze zrobić subtaska na Jira i w treści lub nazwie wpisać swój nick z GitHub.

Lista komend:

    git config --global user.name ""
    git reset HEAD
    gitk -all
    git branch --merged
    git branch "branch" "commit hash"
   
    git pull "remote" "branch"
    git config --global user.email ""
    git diff --staged
    git checkout -b "branch"
    git log --graph --all
    
    git branch -d "branch"
    git fetch "remote" "branch"
    git config --global color.ui true
    git commit "filename"
    git branch -v
    
    git push "remote" "branch"
    git log "branch" --not "branch"
    git bisect (start, bad, good, reset)
    git clone /path/to/repository
    git init

