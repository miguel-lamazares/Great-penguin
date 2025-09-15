sudo apt install zsh 
zsh-autosuggestions
zsh-syntax-highlighting

git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git

utilize o comando cat .zshrc

com nano utilize o comando ~/.zshrc

source /usr/share/zsh-autosuggestions/zsh-autosuggestions.zsh
source /usr/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source $HOME/zsh-autocomplete/zsh-autocomplete.plugin.zsh

para trasformalo padrao use o comando which zsh
normalmente este e o caminho basta adicionalo em caminho personalizado
/usr/bin/zsh