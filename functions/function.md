function d{



param(

\[string]$msg = 'atualização automática'

)



git add .

git commit -m $msg

git push



}

