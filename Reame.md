<h1>Exercice 1</h1>
<h2>l'outil qui me permettra de versionner mon code est Git .</h2>
<h2>l'outil qui me permettra de collaborer avec le second developpeur est Github</h2>
<h2> 
   <b>definition des termes</b>
   <ol>
      <li>VCS : (version control systeme) </li>
      <li>GIT : est un logiciel de gestion de version</li>
      <li>GITHUB : est une entreprise de developpement et service logiciel</li>
   </ol>
</h2>

<h2> 
    la difference est que Git est un outil de versinonnage de code et que Github est une entreprise de developpement
</h2>

<h2> 
   il est indispensable pour le developpeur car il pourra sauvegarder plusieur version de ces projet et les modifier
   en cas de besoin
</h2>

<h2>
   SSH : protocole permettent de manager une machine dans un reseau. il sert a se connecte  a une machine(virtuel) dans  un reseau a fin de d'interagir  sur cet machine
</h2>

<h2>
   En SSH il existe deux types de cles qui sont utilises on a :
   <ul>
      <li>la cle prive</li>
      <li>la cle public</li>
   </ul>
</h2>

<h2>
   Pour se connecter a GITHUB en utilisant le SSH nous devons :
   <ol>
      <li>creer tout d'abord un compte sur GITHUB.com</li>
      <li>
        En suite aller sur le site de git.com et telecharger le logiciel git sur windows (si vous etes dans une discri   bution linus aller dans dans le terminal puis tapez la commande <b>sudo apt-get install git</b>)
      </li>
      <li>puis demarrer le logiciel git bash sur windows, sous linux vous devez juste ouvrir le terminal</li>
      <li> 
        puis proceder a l'identification en tapent la commande <b><u>git config --global user.name "username" <u></ b>, <b><u>git config --global user.email "email" <u></b>, <b><u>git config --global user.password "password" <u></b>, <i>NB: remplacer par les elements qui correspondent dans le d'ouble cote </i> (windows et linux).
      </li>
      <li>
        puis tapez la commande <b> ssh-keygen</b> (windows et linux).
      </li>
      <li>
         En suite appuyer  sur "entrer" pour repondre a la premiere question.
         puis appuyer "y" pour yes pour la prochainne question, ensuite appuyer sur entrer pour toute les questions restantes ( windows et linux).
      </li> 
      <li>puis tapez la commande <b> cat ~/.ssh/id_rsa.pub</b> cela vous genererras votre cle public vous allez copier</li>
      <ul>
         puis dans  github cliquer sur votre icone d'utilisateur placer a l'extreme droite, dansla session qui souvre scrolle vers le bas et cliquer sur setting, dans la nouvel session ouverte cliquer sur <b> SSH and GPG keys</b>
      </li>
      <li>
         puis cliquer sur <b>New SSH key</b> 
         ensuite donner un nom a votre cle dans le premier block, dans le deuxieme block coller la cle public que vous avez copiez precedemment et cliquer sur <b>add ssh key</b> .
      </li>
      <li>fin</li>
   </ol>
</h2>

<h2>
  la difference entre local repository et le remote repository est que le local est situe dans votre propre machine et que le remote est situe dans un serveur distant
</h2>