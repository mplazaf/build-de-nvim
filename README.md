1) init.lua está en 
~/.config/nvim
lo primero que hay que hacer es crear este directorio
2) en este directorio crear
   - mkdir lua
   y dentro de este
   - mkdir config
   - mkdir plugins
  
ESTO ES SOLO PARA BORRAR LA CONFIGURACION QUE TENIA ANTES DE ESTA, SI SE EJECUTA ESTO SE RESTAURARÁ NVIM DE 0
mv ~/.config/nvim ~/.config/nvim_backup
mv ~/.local/share/nvim ~/.local/share/nvim_backup
mv ~/.local/state/nvim ~/.local/state/nvim_backup
mv ~/.cache/nvim ~/.cache/nvim_backup  
