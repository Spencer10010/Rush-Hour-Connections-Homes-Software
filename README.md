# Rush-Hour-Connections-Homes-Software
KSU 2022 Hackathon by Group Rush Hour 2

people := RECORD
  STRING first;
  STRING last;
  INTEGER christian;
  INTEGER muslim;
  INTEGER jewish;
  INTEGER hindu;
  INTEGER buddhist;
  INTEGER other;
  INTEGER spiritual;
  INTEGER none;
  INTEGER alchoholOccasion;
  INTEGER alchoholResponsible;
  INTEGER alchoholIrresponsible;
  INTEGER drug;
  INTEGER marijuanaOccasion;
  INTEGER marijuanaReg;
  INTEGER cigReg;
  INTEGER cigOccasion;
  INTEGER vapeOccasion;
  INTEGER vapeReg;
  INTEGER criminalhistoryArrest;
  INTEGER criminalhistoryJail;
  INTEGER criminalhistoryProbation;
  INTEGER het;
  INTEGER homo;
  INTEGER bi;
  INTEGER male;
  INTEGER female;
  INTEGER trans;
  INTEGER nonBinary;
  REAL latitude;
  REAL longitute;
END;

hosts := DATASET([
  {'Aaron', 'Brantley', 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 34.116912, -82.874767},
  {'Alice', 'Keeney', 5, 4, 3, 4, 4, 5, 4, 2, 5, 1, 2, 5, 5, 4, 4, 1, 3, 5, 2, 2, 1, 5, 4, 5, 1, 5, 3, 5, 32.460432, -83.733486}],
                people);

OUTPUT(hosts, NAMED('hosts'));
