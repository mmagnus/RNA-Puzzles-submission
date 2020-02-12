RNA-Puzzle 24 Adenovirus virus-associated RNA
-----------------------------------------------------------------------------

    rna_pdb_toolsx.py --get-seq *.pdb
    # 24_0_solution_6ol3
    > A:1-34 36-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC

## RMSD
    
    $ rna_calc_rmsd.py -t 24_0_solution_6ol3.pdb  --model-selection=A:1-34+36-112 --target-selection=A:1-34+36-112 *.pdb

    $ csv rmsds.csv
    fn                             rmsd_all
    24_0_solution_6ol3.pdb         0
    24_DasTFN_10_rpr.pdb           4.82
    24_DasTFN_6_rpr.pdb            6.58
    24_FARFAR2_9_rpr.pdb           7.68
    24_DasTFN_9_rpr.pdb            8.93
    24_FARFAR2_6_rpr.pdb           8.93
    24_Bujnicki_2_rpr.pdb          9.75
    24_RNAComposerHuman_5_rpr.pdb  9.85
    24_FARFAR2_10_rpr.pdb          10.12
    24_RNAComposer_2_rpr.pdb       10.24
    24_RNAComposerHuman_1_rpr.pdb  10.27
    24_iFoldRNA_2_rpr.pdb          10.28
    24_DasTFN_8_rpr.pdb            10.63
    24_Bujnicki_3_rpr.pdb          10.77
    24_DasTFN_1_rpr.pdb            10.9
    24_RNAComposerHuman_2_rpr.pdb  10.95
    24_Vfold3D_5_rpr.pdb           11.06
    24_FARFAR2_7_rpr.pdb           12.19
    24_Vfold3D_2_rpr.pdb           12.79
    24_RNAComposer_4_rpr.pdb       12.87
    24_FARFAR2_8_rpr.pdb           12.91
    24_RNAComposer_3_rpr.pdb       13.03
    24_RNAComposer_1_rpr.pdb       13.3
    24_DasTFN_2_rpr.pdb            13.33
    24_FARFAR2_4_rpr.pdb           13.54
    24_Das_7_rpr.pdb               13.61
    24_VfoldLA_5_rpr.pdb           13.7
    24_SimRNA_3_rpr.pdb            13.74
    24_Das_9_rpr.pdb               14.13
    24_Vfold3D_4_rpr.pdb           14.2
    24_VfoldLA_4_rpr.pdb           14.33
    24_RNAComposerHuman_3_rpr.pdb  14.35
    24_Das_5_rpr.pdb               14.36
    24_VfoldLA_3_rpr.pdb           14.36
    24_Bujnicki_5_rpr.pdb          14.57
    24_Das_6_rpr.pdb               14.58
    24_Vfold3D_1_rpr.pdb           14.72
    24_Das_8_rpr.pdb               14.92
    24_Das_4_rpr.pdb               15
    24_VfoldLA_1_rpr.pdb           15.03
    24_RNAComposerHuman_4_rpr.pdb  15.04
    24_Bujnicki_1_rpr.pdb          15.15
    24_VfoldLA_2_rpr.pdb           15.37
    24_SimRNA_5_rpr.pdb            15.43
    24_Vfold3D_3_rpr.pdb           15.47
    24_3dRNA_1_rpr.pdb             15.6
    24_3dRNA_4_rpr.pdb             15.71
    24_Das_1_rpr.pdb               15.92
    24_Das_10_rpr.pdb              16.46
    24_Das_3_rpr.pdb               16.76
    24_DasTFN_3_rpr.pdb            16.78
    24_DasTFN_7_rpr.pdb            16.78
    24_FARFAR2_1_rpr.pdb           16.78
    24_FARFAR2_2_rpr.pdb           16.88
    24_RNAComposer_5_rpr.pdb       17.1
    24_Das_2_rpr.pdb               17.25
    24_Bujnicki_4_rpr.pdb          18.29
    24_3dRNA_3_rpr.pdb             18.32
    24_FARFAR2_5_rpr.pdb           18.38
    24_3dRNA_5_rpr.pdb             18.4
    24_FARFAR2_3_rpr.pdb           19.06
    24_Ding_5_rpr.pdb              19.18
    24_Ding_6_rpr.pdb              19.22
    24_iFoldRNA_1_rpr.pdb          19.38
    24_DasTFN_5_rpr.pdb            19.6
    24_Ding_10_rpr.pdb             19.66
    24_3dRNA_2_rpr.pdb             19.86
    24_Ding_1_rpr.pdb              20.05
    24_iFoldRNA_3_rpr.pdb          20.43
    24_Ding_3_rpr.pdb              20.86
    24_Ding_2_rpr.pdb              20.89
    24_SimRNA_1_rpr.pdb            21.2
    24_Ding_9_rpr.pdb              21.21
    24_DasTFN_4_rpr.pdb            21.93
    24_iFoldRNA_5_rpr.pdb          23.21
    24_Ding_8_rpr.pdb              24
    24_SimRNA_2_rpr.pdb            24.79
    24_Kollmann_2_rpr.pdb          25.34
    24_SimRNA_4_rpr.pdb            26.21
    24_Ding_7_rpr.pdb              26.34
    24_iFoldRNA_4_rpr.pdb          27.16
    24_Ding_4_rpr.pdb              27.76
    24_Kollmann_7_rpr.pdb          29.04
    24_Kollmann_9_rpr.pdb          29.66
    24_Kollmann_10_rpr.pdb         29.67
    24_Kollmann_1_rpr.pdb          30.39
    24_Kollmann_6_rpr.pdb          30.64
    24_Kollmann_4_rpr.pdb          32.2
    24_Kollmann_8_rpr.pdb          32.67
    24_Kollmann_5_rpr.pdb          32.68

## INF

    rna_calc_inf.py -t 24_0_solution_6ol3.pdb *.pdb -f

    csv inf.csv
    target                        fn                                   inf_all  inf_stack  inf_WC  inf_nWC  sns_WC  ppv_WC  sns_nWC  ppv_nWC
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_5_rpr.pdb.outCR            0.468    0.000      0.952   0.436    0.929   0.975   0.571    0.333
    24_0_solution_6ol3.pdb.outCR  24_0_solution_6ol3.pdb.outCR         0.550    0.000      1.000   1.000    1.000   1.000   1.000    1.000
    24_0_solution_6ol3.pdb.outCR  24_Bujnicki_3_rpr.pdb.outCR          0.493    0.094      0.927   0.617    0.905   0.950   0.571    0.667
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_6_rpr.pdb.outCR            0.467    0.000      0.939   0.456    0.905   0.974   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_3dRNA_1_rpr.pdb.outCR             0.460    0.000      0.886   0.571    0.786   1.000   0.571    0.571
    24_0_solution_6ol3.pdb.outCR  24_Bujnicki_4_rpr.pdb.outCR          0.486    0.000      0.941   0.598    0.952   0.930   0.714    0.500
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_7_rpr.pdb.outCR            0.478    0.000      0.952   0.478    0.929   0.975   0.571    0.400
    24_0_solution_6ol3.pdb.outCR  24_3dRNA_2_rpr.pdb.outCR             0.471    0.000      0.886   0.655    0.786   1.000   0.429    1.000
    24_0_solution_6ol3.pdb.outCR  24_Bujnicki_5_rpr.pdb.outCR          0.489    0.000      0.929   0.668    0.929   0.929   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_8_rpr.pdb.outCR            0.473    0.000      0.952   0.456    0.929   0.975   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_3dRNA_3_rpr.pdb.outCR             0.486    0.000      0.951   0.463    0.905   1.000   0.429    0.500
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_10_rpr.pdb.outCR           0.458    0.000      0.951   0.404    0.905   1.000   0.571    0.286
    24_0_solution_6ol3.pdb.outCR  24_3dRNA_4_rpr.pdb.outCR             0.503    0.000      0.951   0.655    0.905   1.000   0.429    1.000
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_9_rpr.pdb.outCR            0.468    0.000      0.952   0.436    0.929   0.975   0.571    0.333
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_1_rpr.pdb.outCR            0.478    0.000      0.964   0.456    0.929   1.000   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_Das_10_rpr.pdb.outCR              0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_3dRNA_5_rpr.pdb.outCR             0.479    0.000      0.926   0.507    0.857   1.000   0.429    0.600
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_2_rpr.pdb.outCR            0.462    0.000      0.939   0.436    0.905   0.974   0.571    0.333
    24_0_solution_6ol3.pdb.outCR  24_Das_1_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_Bujnicki_1_rpr.pdb.outCR          0.489    0.000      0.976   0.478    0.952   1.000   0.571    0.400
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_3_rpr.pdb.outCR            0.473    0.000      0.952   0.456    0.929   0.975   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_Das_2_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_DasTFN_4_rpr.pdb.outCR            0.462    0.000      0.939   0.436    0.905   0.974   0.571    0.333
    24_0_solution_6ol3.pdb.outCR  24_Bujnicki_2_rpr.pdb.outCR          0.495    0.094      0.952   0.535    0.952   0.952   0.571    0.500
    24_0_solution_6ol3.pdb.outCR  24_Das_3_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_Ding_1_rpr.pdb.outCR              0.333    0.094      0.621   0.463    0.429   0.900   0.429    0.500
    24_0_solution_6ol3.pdb.outCR  24_Ding_9_rpr.pdb.outCR              0.339    0.094      0.640   0.378    0.452   0.905   0.286    0.500
    24_0_solution_6ol3.pdb.outCR  24_Ding_2_rpr.pdb.outCR              0.339    0.133      0.621   0.378    0.429   0.900   0.286    0.500
    24_0_solution_6ol3.pdb.outCR  24_Das_4_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_10_rpr.pdb.outCR          0.478    0.000      0.952   0.478    0.929   0.975   0.571    0.400
    24_0_solution_6ol3.pdb.outCR  24_Ding_3_rpr.pdb.outCR              0.348    0.094      0.640   0.507    0.452   0.905   0.429    0.600
    24_0_solution_6ol3.pdb.outCR  24_Das_5_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_1_rpr.pdb.outCR           0.473    0.000      0.952   0.456    0.929   0.975   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_Ding_4_rpr.pdb.outCR              0.321    0.133      0.606   0.309    0.429   0.857   0.286    0.333
    24_0_solution_6ol3.pdb.outCR  24_Das_6_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_2_rpr.pdb.outCR           0.451    0.000      0.952   0.378    0.929   0.975   0.571    0.250
    24_0_solution_6ol3.pdb.outCR  24_Ding_5_rpr.pdb.outCR              0.330    0.094      0.658   0.286    0.476   0.909   0.286    0.286
    24_0_solution_6ol3.pdb.outCR  24_Das_7_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_3_rpr.pdb.outCR           0.473    0.000      0.952   0.456    0.929   0.975   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_Ding_6_rpr.pdb.outCR              0.316    0.133      0.621   0.267    0.429   0.900   0.286    0.250
    24_0_solution_6ol3.pdb.outCR  24_Das_8_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_Ding_7_rpr.pdb.outCR              0.350    0.188      0.621   0.338    0.429   0.900   0.286    0.400
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_4_rpr.pdb.outCR           0.460    0.000      0.926   0.456    0.881   0.974   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_Das_9_rpr.pdb.outCR               0.522    0.000      1.000   0.668    1.000   1.000   0.714    0.625
    24_0_solution_6ol3.pdb.outCR  24_Ding_8_rpr.pdb.outCR              0.321    0.094      0.621   0.401    0.429   0.900   0.429    0.375
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_5_rpr.pdb.outCR           0.467    0.000      0.939   0.456    0.905   0.974   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_Ding_10_rpr.pdb.outCR             0.339    0.133      0.640   0.401    0.452   0.905   0.429    0.375
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_7_rpr.pdb.outCR           0.471    0.000      0.939   0.478    0.905   0.974   0.571    0.400
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_6_rpr.pdb.outCR           0.468    0.000      0.952   0.436    0.929   0.975   0.571    0.333
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_8_rpr.pdb.outCR           0.498    0.000      0.964   0.571    0.929   1.000   0.571    0.571
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_5_rpr.pdb.outCR          0.318    0.000      0.627   0.286    0.619   0.634   0.286    0.286
    24_0_solution_6ol3.pdb.outCR  24_RNAComposerHuman_4_rpr.pdb.outCR  0.488    0.000      0.964   0.504    0.929   1.000   0.571    0.444
    24_0_solution_6ol3.pdb.outCR  24_FARFAR2_9_rpr.pdb.outCR           0.478    0.000      0.952   0.478    0.929   0.975   0.571    0.400
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_6_rpr.pdb.outCR          0.243    0.133      0.451   0.154    0.429   0.474   0.143    0.167
    24_0_solution_6ol3.pdb.outCR  24_RNAComposerHuman_5_rpr.pdb.outCR  0.484    0.000      0.976   0.456    0.952   1.000   0.571    0.364
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_10_rpr.pdb.outCR         0.109    0.000      0.247   0.000    0.238   0.256   0.000    0.000
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_7_rpr.pdb.outCR          0.144    0.000      0.304   0.105    0.286   0.324   0.143    0.077
    24_0_solution_6ol3.pdb.outCR  24_RNAComposer_1_rpr.pdb.outCR       0.487    0.000      0.951   0.535    0.905   1.000   0.571    0.500
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_1_rpr.pdb.outCR          0.284    0.000      0.566   0.267    0.524   0.611   0.286    0.250
    24_0_solution_6ol3.pdb.outCR  24_RNAComposer_2_rpr.pdb.outCR       0.480    0.000      0.951   0.429    0.905   1.000   0.429    0.429
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_8_rpr.pdb.outCR          0.232    0.000      0.476   0.134    0.452   0.500   0.143    0.125
    24_0_solution_6ol3.pdb.outCR  24_RNAComposer_3_rpr.pdb.outCR       0.462    0.000      0.913   0.504    0.833   1.000   0.571    0.444
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_9_rpr.pdb.outCR          0.107    0.094      0.203   0.000    0.190   0.216   0.000    0.000
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_2_rpr.pdb.outCR          0.236    0.094      0.489   0.109    0.452   0.528   0.143    0.083
    24_0_solution_6ol3.pdb.outCR  24_RNAComposer_4_rpr.pdb.outCR       0.504    0.000      0.964   0.617    0.929   1.000   0.571    0.667
    24_0_solution_6ol3.pdb.outCR  24_RNAComposerHuman_1_rpr.pdb.outCR  0.457    0.000      0.888   0.535    0.833   0.946   0.571    0.500
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_3_rpr.pdb.outCR          0.240    0.000      0.503   0.126    0.452   0.559   0.143    0.111
    24_0_solution_6ol3.pdb.outCR  24_RNAComposer_5_rpr.pdb.outCR       0.447    0.000      0.888   0.478    0.833   0.946   0.571    0.400
    24_0_solution_6ol3.pdb.outCR  24_RNAComposerHuman_2_rpr.pdb.outCR  0.479    0.000      0.926   0.571    0.857   1.000   0.571    0.571
    24_0_solution_6ol3.pdb.outCR  24_Kollmann_4_rpr.pdb.outCR          0.223    0.000      0.499   0.101    0.429   0.581   0.143    0.071
    24_0_solution_6ol3.pdb.outCR  24_SimRNA_1_rpr.pdb.outCR            0.284    0.000      0.551   0.359    0.524   0.579   0.429    0.300
    24_0_solution_6ol3.pdb.outCR  24_RNAComposerHuman_3_rpr.pdb.outCR  0.493    0.000      0.964   0.535    0.929   1.000   0.571    0.500
    24_0_solution_6ol3.pdb.outCR  24_SimRNA_2_rpr.pdb.outCR            0.104    0.000      0.206   0.120    0.190   0.222   0.143    0.100
    24_0_solution_6ol3.pdb.outCR  24_Vfold3D_5_rpr.pdb.outCR           0.527    0.000      0.976   0.845    0.952   1.000   0.714    1.000
    24_0_solution_6ol3.pdb.outCR  24_iFoldRNA_3_rpr.pdb.outCR          0.400    0.000      0.766   0.436    0.738   0.795   0.286    0.667
    24_0_solution_6ol3.pdb.outCR  24_SimRNA_3_rpr.pdb.outCR            0.314    0.000      0.651   0.228    0.619   0.684   0.286    0.182
    24_0_solution_6ol3.pdb.outCR  24_VfoldLA_1_rpr.pdb.outCR           0.503    0.094      0.951   0.535    0.905   1.000   0.286    1.000
    24_0_solution_6ol3.pdb.outCR  24_iFoldRNA_4_rpr.pdb.outCR          0.315    0.000      0.610   0.267    0.524   0.710   0.143    0.500
    24_0_solution_6ol3.pdb.outCR  24_SimRNA_4_rpr.pdb.outCR            0.202    0.000      0.381   0.286    0.381   0.381   0.286    0.286
    24_0_solution_6ol3.pdb.outCR  24_VfoldLA_2_rpr.pdb.outCR           0.497    0.000      0.926   0.756    0.857   1.000   0.571    1.000
    24_0_solution_6ol3.pdb.outCR  24_iFoldRNA_5_rpr.pdb.outCR          0.368    0.094      0.720   0.189    0.667   0.778   0.143    0.250
    24_0_solution_6ol3.pdb.outCR  24_SimRNA_5_rpr.pdb.outCR            0.328    0.000      0.642   0.309    0.619   0.667   0.286    0.333
    24_0_solution_6ol3.pdb.outCR  24_VfoldLA_3_rpr.pdb.outCR           0.497    0.000      0.939   0.676    0.881   1.000   0.571    0.800
    24_0_solution_6ol3.pdb.outCR  24_Vfold3D_1_rpr.pdb.outCR           0.521    0.000      0.976   0.772    0.952   1.000   0.714    0.833
    24_0_solution_6ol3.pdb.outCR  24_VfoldLA_4_rpr.pdb.outCR           0.497    0.000      0.926   0.756    0.857   1.000   0.571    1.000
    24_0_solution_6ol3.pdb.outCR  24_Vfold3D_2_rpr.pdb.outCR           0.527    0.000      0.976   0.845    0.952   1.000   0.714    1.000
    24_0_solution_6ol3.pdb.outCR  24_VfoldLA_5_rpr.pdb.outCR           0.509    0.163      0.913   0.756    0.833   1.000   0.571    1.000
    24_0_solution_6ol3.pdb.outCR  24_Vfold3D_3_rpr.pdb.outCR           0.521    0.000      0.976   0.772    0.952   1.000   0.714    0.833
    24_0_solution_6ol3.pdb.outCR  24_iFoldRNA_1_rpr.pdb.outCR          0.503    0.000      0.964   0.567    0.929   1.000   0.429    0.750
    24_0_solution_6ol3.pdb.outCR  24_Vfold3D_4_rpr.pdb.outCR           0.497    0.000      0.951   0.617    0.905   1.000   0.571    0.667
    24_0_solution_6ol3.pdb.outCR  24_iFoldRNA_2_rpr.pdb.outCR          0.468    0.000      0.939   0.401    0.881   1.000   0.429    0.375

## Sequences

This solution was renumber to:

    $ rna_pdb_toolsx.py --get-seq 24_0_solution_6ol3.pdb
    # 24_0_solution_6ol3
    > A:1-34 36-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC

so no RMSD and INF can be calculated.

Raw data:

    rna_pdb_toolsx.py --get-seq *.pdb
    # 24_0_solution_6ol3
    > A:26-59 61-137
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_3dRNA_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_3dRNA_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_3dRNA_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_3dRNA_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_3dRNA_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Bujnicki_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Bujnicki_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Bujnicki_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Bujnicki_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Bujnicki_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_10_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_6_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_7_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_8_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_DasTFN_9_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_10_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_6_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_7_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_8_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Das_9_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_10_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_6_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_7_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_8_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Ding_9_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_10_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_6_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_7_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_8_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_FARFAR2_9_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_10_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_6_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_7_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_8_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Kollmann_9_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposerHuman_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposerHuman_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposerHuman_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposerHuman_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposerHuman_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposer_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposer_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposer_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposer_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_RNAComposer_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_SimRNA_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_SimRNA_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_SimRNA_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_SimRNA_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_SimRNA_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Vfold3D_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Vfold3D_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Vfold3D_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Vfold3D_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_Vfold3D_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_VfoldLA_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_VfoldLA_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_VfoldLA_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_VfoldLA_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_VfoldLA_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_iFoldRNA_1_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_iFoldRNA_2_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_iFoldRNA_3_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_iFoldRNA_4_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC
    # 24_iFoldRNA_5_rpr
    > A:1-112
    GGACCUCGCAAGGGUAUCAUGGCGGACGACCGGGGUUCGAACCCCGGAUCCGGCCGUCCGCCGUGAUCCAUGCGGUUACCGCCCGCGUGUCGAACCCAGGUGUGCGAGGUCC