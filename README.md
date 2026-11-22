Locked deck-builder kit.
Unlock:  cat deckkit.tar.enc.part* | openssl enc -d -aes-256-cbc -pbkdf2 -iter 200000 -pass pass:PASSWORD | tar xf -
Gives deckkit_code.zip and deckkit_pics.zip. Unzip both into /home/claude.
