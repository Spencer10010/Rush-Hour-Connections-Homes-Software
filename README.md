# Rush-Hour-Connections-Homes-Software
KSU 2022 Hackathon by Group Rush Hour 2

people := RECORD
  STRING first;
  STRING last;
  //STRING 'religion';
  INTEGER christian;
  INTEGER muslim;
  INTEGER jewish;
  INTEGER hindu;
  INTEGER buddhist;
  INTEGER other;
  INTEGER spiritual;
  INTEGER none;
  INTEGER aOccasion;
  INTEGER aResponsible;
  INTEGER aIrresponsible;
  INTEGER drug;
  INTEGER mOccasional;
  INTEGER mRegular;
  INTEGER cRegular;
  INTEGER cOccasional;
  INTEGER vOccasional;
  INTEGER vRegular;
  INTEGER chArrested;
  INTEGER chJail;
  INTEGER chProbation;
  INTEGER het;
  INTEGER homo;
  INTEGER bi;
  REAL latitude;
  REAL longitute;
END;

hosts := DATASET([
  {'Aaron', 'Brantley', 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 34.116912, 82.874767},
  {'Alice', 'Keeney', 5, 4, 3, 4, 4, 5, 4, 2, 5, 1, 2, 5, 5, 4, 4, 1, 3, 5, 2, 2, 1, 5, 4, 5, 34.116912, 82.874767}],
                people);

OUTPUT(hosts, NAMED('hosts'));
