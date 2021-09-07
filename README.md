# Youtube channel ripping


This txt file has all the download links i already have downloaded



these are the aliasses i used to rip a channel



alias edubois='youtube-dl --download-archive ~/Videos/edubois.txt -f best -ciw -o "%(upload_date)s - %(title)s.%(ext)s" -v https://www.youtube.com/ErikDubois'

alias redubois='youtube-dl --playlist-reverse --download-archive ~/Videos/edubois.txt -f best -ciw -o "%(upload_date)s - %(title)s.%(ext)s" -v https://www.youtube.com/ErikDubois'

alias ytr='youtube-dl -f best -ciw -o "%(upload_date)s - %(title)s.%(ext)s" -v '

alias ytrr='youtube-dl --playlist-reverse -f best -ciw -o "%(upload_date)s - %(title)s.%(ext)s" -v '