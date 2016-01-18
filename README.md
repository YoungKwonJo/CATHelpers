# CATHelpers

ref. https://twiki.cern.ch/twiki/bin/view/CMS/BTagShapeCalibration#Using_histogram_files

\#include "CATHelpers/CSVHelper/interface/CSVHelper.h"

:

  CSVHelper *csvWeight;

:

  csvWeight = new CSVHelper();

:

        b_csvweight         = csvWeight->getCSVWeight(selectedJets, 0);//); 
        b_csvweight_JES_Up  = csvWeight->getCSVWeight(selectedJets, 7);
        b_csvweight_JES_Down= csvWeight->getCSVWeight(selectedJets, 8);
        b_csvweight_LF_Up   = csvWeight->getCSVWeight(selectedJets, 9);
        b_csvweight_LF_Down = csvWeight->getCSVWeight(selectedJets, 10);
        b_csvweight_HF_Up   = csvWeight->getCSVWeight(selectedJets, 11);
        b_csvweight_HF_Down = csvWeight->getCSVWeight(selectedJets, 12);
        b_csvweight_HF_Stats1_Up  = csvWeight->getCSVWeight(selectedJets, 13);
        b_csvweight_HF_Stats1_Down= csvWeight->getCSVWeight(selectedJets, 14);
        b_csvweight_HF_Stats2_Up  = csvWeight->getCSVWeight(selectedJets, 15);
        b_csvweight_HF_Stats2_Down= csvWeight->getCSVWeight(selectedJets, 16);
        b_csvweight_LF_Stats1_Up  = csvWeight->getCSVWeight(selectedJets, 17);
        b_csvweight_LF_Stats1_Down= csvWeight->getCSVWeight(selectedJets, 18);
        b_csvweight_LF_Stats2_Up  = csvWeight->getCSVWeight(selectedJets, 19);
        b_csvweight_LF_Stats2_Down= csvWeight->getCSVWeight(selectedJets, 20);
        b_csvweight_Charm_Err1_Up = csvWeight->getCSVWeight(selectedJets, 21);
        b_csvweight_Charm_Err1_Down= csvWeight->getCSVWeight(selectedJets, 22);
        b_csvweight_Charm_Err2_Up  = csvWeight->getCSVWeight(selectedJets, 23);
        b_csvweight_Charm_Err2_Down= csvWeight->getCSVWeight(selectedJets, 24);

