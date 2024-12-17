
<h2><p align="center">💥💥 Resutados do Desafio Bootcamp Santander#2 💥💥</p></h2>
<h4><p align="center"> Ataques DoS no Windows RDP  </p></h4>
<h4><p align="center"> Técnicas de Exploração de Vulnerabilidades </p></h4>

                          
<h4><p align="left"> - Exploração </p></h4>

<p>
<img
    align="justify" 
    width="550px" 
    height="250px"
    src="https://github.com/user-attachments/assets/8c0c67e8-1841-4815-ad57-79794c07635a"
/>
</p>


<p align="justify">O serviço RDP pode ser configurado por administradores de sistemas Windows para ser executado em TCP (geralmente na porta 3389) e/ou na porta UDP (3389). 
Os ataques RDP são tentativas de agentes de ameaças de acessar um host de desktop remoto ou privilégios administrativos do cliente para reconhecimento, comando e controle e movimentação lateral.</p>


<p>
<img
    align="justify" 
    width="550px" 
    height="250px"
    src="https://github.com/user-attachments/assets/6c4f1d90-1dd6-44d9-9a16-4ab8d8c83bb6"
/>
</p>


<h4><p align="left"> Tipos de taques RDP </p></h4>

🔸Calling Into Robinhood

🔸SamSam Ransomware

<h4><p align="left"> Prevenção </p></h4>

✔ Autenticação multifator e requisitos complexos de credenciais de acesso

✔ Estabelecer políticas de bloqueio de conta para tentativas de força bruta

✔ Controle de acesso baseado em função (RBAC) para consoles RDP

✔ Restrições de acesso RDP baseadas em firewall.

<h4><p align="left"> Prática Vamos simular um ataque em nossa máquina virtual Windows </p></h4>

-Acessar msfconsole pelo kali linux, buscar por RDP, setar para o IP a ser atacado e executar comando RUN

1 - use auxiliary/dos/windows/rdp/ms12_020_maxchannelids

2 - set [RHOSTS], replacing [RHOSTS] with a list of hosts to test for the presence of RDP

3 - run

4 - A estação de trabalho será reiniciada -  TELA AZUL

<p>
<img
    align="justify" 
    width="550px" 
    height="250px"
    src="https://github.com/user-attachments/assets/7e168c93-2108-407c-a431-4901647c5d4f"
/>
</p>



<p>
<img
    align="justify" 
    width="550px" 
    height="250px"
    src="https://github.com/user-attachments/assets/db101319-72a9-4d6b-9d29-0c2ce45b3cd8"
/>
</p>


<p>
<img 
    align="justify" 
    width="550px" 
    height="250px"
    src="https://github.com/user-attachments/assets/08dcdabf-f36a-4985-a757-6a80c511013b"
/>
</p>

