# Wheelchair-Instrumentation-GUI
Gauges that measure Temp, Strain, Accel, and Velocity

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package demo1;

/**
 *
 * @author bonnie
 */




public class MainFrm extends javax.swing.JFrame {
    //import java.util.Calendar;
    //import java.util.GregorianCalendar;
    
    
    
    /**
     * Creates new form MainFrm
     */
    public MainFrm() {
        initComponents();
        //showDate();
       // showTime();
    }
//    public void showDate() {
//        Calendar cal = new GregorianCalendar();
//        int month = cal.get(Calendar.MONTH);
//        int year = cal.get(Calendar.YEAR);
//        int day = cal.get(Calendar.DAY_OF_MONTH);
//        DateLab.setText((month+1)+"/"+"/"+day+"/"+year);
//        
//    }
//    void showTime() {
//        new Timer(0, new ActionListener() {
//            @Override
//            public void actionPerformed(ActionEvent e) {
//                Date d = new Date();
//                SimpleDateFormat s = new SimpleDateFormat("hh:mm:ss a");
//                TimeLab.setText(s.format(d));               
//            }
//        }).start();
//    }
 
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        linearBargraphBeanInfo1 = new eu.hansolo.steelseries.gauges.LinearBargraphBeanInfo();
        radialBargraphBeanInfo1 = new eu.hansolo.steelseries.gauges.RadialBargraphBeanInfo();
        menuBar1 = new java.awt.MenuBar();
        menu1 = new java.awt.Menu();
        menu2 = new java.awt.Menu();
        linear2 = new org.pushingpixels.trident.ease.Linear();
        jScrollPane1 = new javax.swing.JScrollPane();
        jTextArea1 = new javax.swing.JTextArea();
        RPMGauge = new eu.hansolo.steelseries.gauges.RadialBargraph();
        startButton1 = new javax.swing.JButton();
        stopButton2 = new javax.swing.JButton();
        jTextField2 = new javax.swing.JTextField();
        jTextField3 = new javax.swing.JTextField();
        jTextField4 = new javax.swing.JTextField();
        TimeLabel1 = new javax.swing.JLabel();
        RunTimeLabel2 = new javax.swing.JLabel();
        TestNoLabel3 = new javax.swing.JLabel();
        RoomTempLabel4 = new javax.swing.JLabel();
        jPanel1 = new javax.swing.JPanel();
        Temp_FL = new eu.hansolo.steelseries.gauges.LinearBargraph();
        Strain_FL = new eu.hansolo.steelseries.gauges.Linear();
        AccZ_FL = new eu.hansolo.steelseries.gauges.Linear();
        jLabel6 = new javax.swing.JLabel();
        jDesktopPane1 = new javax.swing.JDesktopPane();
        AccLabel1 = new javax.swing.JLabel();
        label1 = new java.awt.Label();
        jPanel2 = new javax.swing.JPanel();
        Temp_RL = new eu.hansolo.steelseries.gauges.LinearBargraph();
        Strain_RL = new eu.hansolo.steelseries.gauges.Linear();
        AccZ_RL = new eu.hansolo.steelseries.gauges.Linear();
        jLabel7 = new javax.swing.JLabel();
        jDesktopPane2 = new javax.swing.JDesktopPane();
        AccLabel3 = new javax.swing.JLabel();
        label3 = new java.awt.Label();
        jPanel3 = new javax.swing.JPanel();
        Temp_FR = new eu.hansolo.steelseries.gauges.LinearBargraph();
        Strain_FR = new eu.hansolo.steelseries.gauges.Linear();
        AccZ_FR = new eu.hansolo.steelseries.gauges.Linear();
        jLabel9 = new javax.swing.JLabel();
        jDesktopPane3 = new javax.swing.JDesktopPane();
        AccLabel2 = new javax.swing.JLabel();
        label2 = new java.awt.Label();
        jPanel4 = new javax.swing.JPanel();
        Temp_RR = new eu.hansolo.steelseries.gauges.LinearBargraph();
        Strain_RR = new eu.hansolo.steelseries.gauges.Linear();
        AccZ_RR = new eu.hansolo.steelseries.gauges.Linear();
        jLabel11 = new javax.swing.JLabel();
        jDesktopPane4 = new javax.swing.JDesktopPane();
        AccLabel4 = new javax.swing.JLabel();
        label4 = new java.awt.Label();
        jButton1 = new javax.swing.JButton();
        TimeLabel2 = new javax.swing.JLabel();
        jDateChooser2 = new com.toedter.calendar.JDateChooser();
        jMenuBar1 = new javax.swing.JMenuBar();
        jMenu1 = new javax.swing.JMenu();
        jMenu2 = new javax.swing.JMenu();

        menu1.setLabel("File");
        menuBar1.add(menu1);

        menu2.setLabel("Edit");
        menuBar1.add(menu2);

        jTextArea1.setColumns(20);
        jTextArea1.setRows(5);
        jScrollPane1.setViewportView(jTextArea1);

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        RPMGauge.setBackground(new java.awt.Color(255, 255, 255));
        RPMGauge.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.BRUSHED_METAL);
        RPMGauge.setBarGraphColor(eu.hansolo.steelseries.tools.ColorDef.GREEN);
        RPMGauge.setCustomBarGraphColor(new java.awt.Color(255, 255, 255));
        RPMGauge.setCustomLcdUnitFont(new java.awt.Font("Times New Roman", 1, 36)); // NOI18N
        RPMGauge.setCustomLcdUnitFontEnabled(true);
        RPMGauge.setFocusable(false);
        RPMGauge.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        RPMGauge.setLcdUnitString("RPM");
        RPMGauge.setMaxMeasuredValueVisible(true);
        RPMGauge.setMaxValue(90.0);
        RPMGauge.setMaximumSize(new java.awt.Dimension(40000, 40000));
        RPMGauge.setMinMeasuredValueVisible(true);
        RPMGauge.setName("Speed"); // NOI18N
        RPMGauge.setSize(new java.awt.Dimension(10, 10));
        RPMGauge.setThresholdVisible(true);
        RPMGauge.setTitle("RPM");
        RPMGauge.setTitleAndUnitFont(new java.awt.Font("3ds Light", 1, 14)); // NOI18N
        RPMGauge.setValue(35
            45
            75
            85
            0);

        startButton1.setBackground(new java.awt.Color(102, 255, 102));
        startButton1.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        startButton1.setText("Start");
        startButton1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                startButton1ActionPerformed(evt);
            }
        });

        stopButton2.setBackground(new java.awt.Color(255, 51, 51));
        stopButton2.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        stopButton2.setText("Stop");
        stopButton2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                stopButton2ActionPerformed(evt);
            }
        });

        TimeLabel1.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        TimeLabel1.setText("Time");

        RunTimeLabel2.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        RunTimeLabel2.setText("Run Time");

        TestNoLabel3.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        TestNoLabel3.setText("Test #");

        RoomTempLabel4.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        RoomTempLabel4.setText("Room Temp.");

        jPanel1.setBorder(javax.swing.BorderFactory.createLineBorder(new java.awt.Color(0, 0, 0), 2));

        Temp_FL.setAutoscrolls(true);
        Temp_FL.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.LIGHT_GRAY);
        Temp_FL.setCustomBarGraphColor(java.awt.Color.white);
        Temp_FL.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.NO_FRAME);
        Temp_FL.setLabelColorFromThemeEnabled(false);
        Temp_FL.setLabelNumberFormat(eu.hansolo.steelseries.tools.NumberFormat.STANDARD);
        Temp_FL.setLcdColor(eu.hansolo.steelseries.tools.LcdColor.STANDARD_LCD);
        Temp_FL.setLcdUnitString("C");
        Temp_FL.setLcdUnitStringVisible(true);
        Temp_FL.setName("Temp_FL"); // NOI18N
        Temp_FL.setOrientation(eu.hansolo.steelseries.tools.Orientation.VERTICAL);
        Temp_FL.setTitle("Temperature");
        Temp_FL.setTitleAndUnitFontEnabled(true);
        Temp_FL.setTrackStart(40.0);
        Temp_FL.setTrackVisible(true);
        Temp_FL.setUnitString("C");
        Temp_FL.setValue(50.0);

        Strain_FL.setBorder(javax.swing.BorderFactory.createEmptyBorder(1, 1, 1, 1));
        Strain_FL.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.TRANSPARENT);
        Strain_FL.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        Strain_FL.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.NO_FRAME);
        Strain_FL.setLedVisible(false);
        Strain_FL.setTitle("Strain");
        Strain_FL.setTitleAndUnitFont(new java.awt.Font("Verdana", 0, 18)); // NOI18N

        AccZ_FL.setBorder(javax.swing.BorderFactory.createEmptyBorder(1, 1, 1, 1));
        AccZ_FL.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.TRANSPARENT);
        AccZ_FL.setCustomLcdBackground(null);
        AccZ_FL.setCustomLcdUnitFontEnabled(true);
        AccZ_FL.setForegroundVisible(false);
        AccZ_FL.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.BLACK_METAL);
        AccZ_FL.setFrameVisible(false);
        AccZ_FL.setLcdVisible(false);
        AccZ_FL.setLedVisible(false);
        AccZ_FL.setMaxValue(3.0);
        AccZ_FL.setThreshold(1.5);
        AccZ_FL.setThresholdVisible(true);
        AccZ_FL.setTitle("");
        AccZ_FL.setTitleVisible(false);

        jLabel6.setText("Z");
        AccZ_FL.add(jLabel6);
        jLabel6.setBounds(60, 260, 20, 20);

        javax.swing.GroupLayout jDesktopPane1Layout = new javax.swing.GroupLayout(jDesktopPane1);
        jDesktopPane1.setLayout(jDesktopPane1Layout);
        jDesktopPane1Layout.setHorizontalGroup(
            jDesktopPane1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGap(0, 251, Short.MAX_VALUE)
        );
        jDesktopPane1Layout.setVerticalGroup(
            jDesktopPane1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGap(0, 227, Short.MAX_VALUE)
        );

        AccLabel1.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        AccLabel1.setText("Accelerometer");

        javax.swing.GroupLayout jPanel1Layout = new javax.swing.GroupLayout(jPanel1);
        jPanel1.setLayout(jPanel1Layout);
        jPanel1Layout.setHorizontalGroup(
            jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel1Layout.createSequentialGroup()
                .addComponent(Temp_FL, javax.swing.GroupLayout.PREFERRED_SIZE, 109, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel1Layout.createSequentialGroup()
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(Strain_FL, javax.swing.GroupLayout.PREFERRED_SIZE, 386, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(jPanel1Layout.createSequentialGroup()
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel1Layout.createSequentialGroup()
                                .addGap(103, 103, 103)
                                .addComponent(AccLabel1))
                            .addComponent(jDesktopPane1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                        .addGap(0, 0, 0)
                        .addComponent(AccZ_FL, javax.swing.GroupLayout.PREFERRED_SIZE, 130, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addGap(0, 0, Short.MAX_VALUE))
        );
        jPanel1Layout.setVerticalGroup(
            jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel1Layout.createSequentialGroup()
                .addGap(0, 0, Short.MAX_VALUE)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel1Layout.createSequentialGroup()
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel1Layout.createSequentialGroup()
                                .addGap(25, 25, 25)
                                .addComponent(AccLabel1)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addComponent(jDesktopPane1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                            .addGroup(jPanel1Layout.createSequentialGroup()
                                .addGap(0, 0, Short.MAX_VALUE)
                                .addComponent(AccZ_FL, javax.swing.GroupLayout.PREFERRED_SIZE, 288, javax.swing.GroupLayout.PREFERRED_SIZE)))
                        .addComponent(Strain_FL, javax.swing.GroupLayout.PREFERRED_SIZE, 116, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addComponent(Temp_FL, javax.swing.GroupLayout.PREFERRED_SIZE, 423, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(0, 0, Short.MAX_VALUE))
        );

        label1.setAlignment(java.awt.Label.CENTER);
        label1.setCursor(new java.awt.Cursor(java.awt.Cursor.DEFAULT_CURSOR));
        label1.setFont(new java.awt.Font("Dialog", 0, 18)); // NOI18N
        label1.setText("Front Left");

        jPanel2.setBorder(javax.swing.BorderFactory.createLineBorder(new java.awt.Color(0, 0, 0), 2));

        Temp_RL.setAutoscrolls(true);
        Temp_RL.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.LIGHT_GRAY);
        Temp_RL.setCustomBarGraphColor(java.awt.Color.white);
        Temp_RL.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.NO_FRAME);
        Temp_RL.setLabelColorFromThemeEnabled(false);
        Temp_RL.setLabelNumberFormat(eu.hansolo.steelseries.tools.NumberFormat.STANDARD);
        Temp_RL.setLcdColor(eu.hansolo.steelseries.tools.LcdColor.STANDARD_LCD);
        Temp_RL.setLcdUnitString("C");
        Temp_RL.setLcdUnitStringVisible(true);
        Temp_RL.setName("Temp_RL"); // NOI18N
        Temp_RL.setOrientation(eu.hansolo.steelseries.tools.Orientation.VERTICAL);
        Temp_RL.setTitle("Temperature");
        Temp_RL.setTitleAndUnitFontEnabled(true);
        Temp_RL.setTrackStart(40.0);
        Temp_RL.setTrackVisible(true);
        Temp_RL.setUnitString("C");
        Temp_RL.setValue(50.0);

        Strain_RL.setBorder(javax.swing.BorderFactory.createEmptyBorder(1, 1, 1, 1));
        Strain_RL.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.TRANSPARENT);
        Strain_RL.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.NO_FRAME);
        Strain_RL.setLedVisible(false);
        Strain_RL.setTitle("Strain");

        AccZ_RL.setBorder(javax.swing.BorderFactory.createEmptyBorder(1, 1, 1, 1));
        AccZ_RL.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.TRANSPARENT);
        AccZ_RL.setForegroundVisible(false);
        AccZ_RL.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.BLACK_METAL);
        AccZ_RL.setFrameVisible(false);
        AccZ_RL.setLcdVisible(false);
        AccZ_RL.setLedVisible(false);
        AccZ_RL.setTitle("");
        AccZ_RL.setTitleVisible(false);

        jLabel7.setText("Z");
        AccZ_RL.add(jLabel7);
        jLabel7.setBounds(60, 260, 20, 20);

        javax.swing.GroupLayout jDesktopPane2Layout = new javax.swing.GroupLayout(jDesktopPane2);
        jDesktopPane2.setLayout(jDesktopPane2Layout);
        jDesktopPane2Layout.setHorizontalGroup(
            jDesktopPane2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGap(0, 251, Short.MAX_VALUE)
        );
        jDesktopPane2Layout.setVerticalGroup(
            jDesktopPane2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGap(0, 227, Short.MAX_VALUE)
        );

        AccLabel3.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        AccLabel3.setText("Accelerometer");

        javax.swing.GroupLayout jPanel2Layout = new javax.swing.GroupLayout(jPanel2);
        jPanel2.setLayout(jPanel2Layout);
        jPanel2Layout.setHorizontalGroup(
            jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel2Layout.createSequentialGroup()
                .addComponent(Temp_RL, javax.swing.GroupLayout.PREFERRED_SIZE, 109, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel2Layout.createSequentialGroup()
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(Strain_RL, javax.swing.GroupLayout.PREFERRED_SIZE, 386, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(jPanel2Layout.createSequentialGroup()
                        .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel2Layout.createSequentialGroup()
                                .addGap(103, 103, 103)
                                .addComponent(AccLabel3))
                            .addComponent(jDesktopPane2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                        .addGap(0, 0, 0)
                        .addComponent(AccZ_RL, javax.swing.GroupLayout.PREFERRED_SIZE, 130, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addGap(0, 0, Short.MAX_VALUE))
        );
        jPanel2Layout.setVerticalGroup(
            jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel2Layout.createSequentialGroup()
                .addGap(0, 0, Short.MAX_VALUE)
                .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel2Layout.createSequentialGroup()
                        .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel2Layout.createSequentialGroup()
                                .addGap(25, 25, 25)
                                .addComponent(AccLabel3)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addComponent(jDesktopPane2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                            .addGroup(jPanel2Layout.createSequentialGroup()
                                .addGap(0, 0, Short.MAX_VALUE)
                                .addComponent(AccZ_RL, javax.swing.GroupLayout.PREFERRED_SIZE, 288, javax.swing.GroupLayout.PREFERRED_SIZE)))
                        .addComponent(Strain_RL, javax.swing.GroupLayout.PREFERRED_SIZE, 116, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addComponent(Temp_RL, javax.swing.GroupLayout.PREFERRED_SIZE, 423, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(0, 0, Short.MAX_VALUE))
        );

        label3.setAlignment(java.awt.Label.CENTER);
        label3.setCursor(new java.awt.Cursor(java.awt.Cursor.DEFAULT_CURSOR));
        label3.setFont(new java.awt.Font("Dialog", 0, 18)); // NOI18N
        label3.setText("Rear Left");

        jPanel3.setBorder(javax.swing.BorderFactory.createLineBorder(new java.awt.Color(0, 0, 0), 2));

        Temp_FR.setAutoscrolls(true);
        Temp_FR.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.LIGHT_GRAY);
        Temp_FR.setCustomBarGraphColor(java.awt.Color.white);
        Temp_FR.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.NO_FRAME);
        Temp_FR.setLabelColorFromThemeEnabled(false);
        Temp_FR.setLabelNumberFormat(eu.hansolo.steelseries.tools.NumberFormat.STANDARD);
        Temp_FR.setLcdColor(eu.hansolo.steelseries.tools.LcdColor.STANDARD_LCD);
        Temp_FR.setLcdUnitString("C");
        Temp_FR.setLcdUnitStringVisible(true);
        Temp_FR.setName("Temp_FR"); // NOI18N
        Temp_FR.setOrientation(eu.hansolo.steelseries.tools.Orientation.VERTICAL);
        Temp_FR.setTitle("Temperature");
        Temp_FR.setTitleAndUnitFontEnabled(true);
        Temp_FR.setTrackStart(40.0);
        Temp_FR.setTrackVisible(true);
        Temp_FR.setUnitString("C");
        Temp_FR.setValue(50.0);

        Strain_FR.setBorder(javax.swing.BorderFactory.createEmptyBorder(1, 1, 1, 1));
        Strain_FR.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.TRANSPARENT);
        Strain_FR.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.NO_FRAME);
        Strain_FR.setLedVisible(false);
        Strain_FR.setTitle("Strain");

        AccZ_FR.setBorder(javax.swing.BorderFactory.createEmptyBorder(1, 1, 1, 1));
        AccZ_FR.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.TRANSPARENT);
        AccZ_FR.setForegroundVisible(false);
        AccZ_FR.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.BLACK_METAL);
        AccZ_FR.setFrameVisible(false);
        AccZ_FR.setLcdVisible(false);
        AccZ_FR.setLedVisible(false);
        AccZ_FR.setTitle("");
        AccZ_FR.setTitleVisible(false);

        jLabel9.setText("Z");
        AccZ_FR.add(jLabel9);
        jLabel9.setBounds(60, 260, 20, 20);

        javax.swing.GroupLayout jDesktopPane3Layout = new javax.swing.GroupLayout(jDesktopPane3);
        jDesktopPane3.setLayout(jDesktopPane3Layout);
        jDesktopPane3Layout.setHorizontalGroup(
            jDesktopPane3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGap(0, 251, Short.MAX_VALUE)
        );
        jDesktopPane3Layout.setVerticalGroup(
            jDesktopPane3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGap(0, 227, Short.MAX_VALUE)
        );

        AccLabel2.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        AccLabel2.setText("Accelerometer");

        javax.swing.GroupLayout jPanel3Layout = new javax.swing.GroupLayout(jPanel3);
        jPanel3.setLayout(jPanel3Layout);
        jPanel3Layout.setHorizontalGroup(
            jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel3Layout.createSequentialGroup()
                .addComponent(Temp_FR, javax.swing.GroupLayout.PREFERRED_SIZE, 109, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel3Layout.createSequentialGroup()
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(Strain_FR, javax.swing.GroupLayout.PREFERRED_SIZE, 386, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(jPanel3Layout.createSequentialGroup()
                        .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel3Layout.createSequentialGroup()
                                .addGap(103, 103, 103)
                                .addComponent(AccLabel2))
                            .addComponent(jDesktopPane3, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                        .addGap(0, 0, 0)
                        .addComponent(AccZ_FR, javax.swing.GroupLayout.PREFERRED_SIZE, 130, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addGap(0, 0, Short.MAX_VALUE))
        );
        jPanel3Layout.setVerticalGroup(
            jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel3Layout.createSequentialGroup()
                .addGap(0, 0, Short.MAX_VALUE)
                .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel3Layout.createSequentialGroup()
                        .addGroup(jPanel3Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel3Layout.createSequentialGroup()
                                .addGap(25, 25, 25)
                                .addComponent(AccLabel2)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addComponent(jDesktopPane3, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                            .addGroup(jPanel3Layout.createSequentialGroup()
                                .addGap(0, 0, Short.MAX_VALUE)
                                .addComponent(AccZ_FR, javax.swing.GroupLayout.PREFERRED_SIZE, 288, javax.swing.GroupLayout.PREFERRED_SIZE)))
                        .addComponent(Strain_FR, javax.swing.GroupLayout.PREFERRED_SIZE, 116, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addComponent(Temp_FR, javax.swing.GroupLayout.PREFERRED_SIZE, 423, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(0, 0, Short.MAX_VALUE))
        );

        label2.setAlignment(java.awt.Label.CENTER);
        label2.setCursor(new java.awt.Cursor(java.awt.Cursor.DEFAULT_CURSOR));
        label2.setFont(new java.awt.Font("Dialog", 0, 18)); // NOI18N
        label2.setText("Front Right");

        jPanel4.setBorder(javax.swing.BorderFactory.createLineBorder(new java.awt.Color(0, 0, 0), 2));

        Temp_RR.setAutoscrolls(true);
        Temp_RR.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.LIGHT_GRAY);
        Temp_RR.setCustomBarGraphColor(java.awt.Color.white);
        Temp_RR.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.NO_FRAME);
        Temp_RR.setLabelColorFromThemeEnabled(false);
        Temp_RR.setLabelNumberFormat(eu.hansolo.steelseries.tools.NumberFormat.STANDARD);
        Temp_RR.setLcdColor(eu.hansolo.steelseries.tools.LcdColor.STANDARD_LCD);
        Temp_RR.setLcdUnitString("C");
        Temp_RR.setLcdUnitStringVisible(true);
        Temp_RR.setName("Temp_RR"); // NOI18N
        Temp_RR.setOrientation(eu.hansolo.steelseries.tools.Orientation.VERTICAL);
        Temp_RR.setTitle("Temperature");
        Temp_RR.setTitleAndUnitFontEnabled(true);
        Temp_RR.setTrackStart(40.0);
        Temp_RR.setTrackVisible(true);
        Temp_RR.setUnitString("C");
        Temp_RR.setValue(50.0);

        Strain_RR.setBorder(javax.swing.BorderFactory.createEmptyBorder(1, 1, 1, 1));
        Strain_RR.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.TRANSPARENT);
        Strain_RR.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.NO_FRAME);
        Strain_RR.setLedVisible(false);
        Strain_RR.setTitle("Strain");

        AccZ_RR.setBorder(javax.swing.BorderFactory.createEmptyBorder(1, 1, 1, 1));
        AccZ_RR.setBackgroundColor(eu.hansolo.steelseries.tools.BackgroundColor.TRANSPARENT);
        AccZ_RR.setForegroundVisible(false);
        AccZ_RR.setFrameDesign(eu.hansolo.steelseries.tools.FrameDesign.BLACK_METAL);
        AccZ_RR.setFrameVisible(false);
        AccZ_RR.setLcdVisible(false);
        AccZ_RR.setLedVisible(false);
        AccZ_RR.setTitle("");
        AccZ_RR.setTitleVisible(false);

        jLabel11.setText("Z");
        AccZ_RR.add(jLabel11);
        jLabel11.setBounds(60, 260, 20, 20);

        javax.swing.GroupLayout jDesktopPane4Layout = new javax.swing.GroupLayout(jDesktopPane4);
        jDesktopPane4.setLayout(jDesktopPane4Layout);
        jDesktopPane4Layout.setHorizontalGroup(
            jDesktopPane4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGap(0, 251, Short.MAX_VALUE)
        );
        jDesktopPane4Layout.setVerticalGroup(
            jDesktopPane4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGap(0, 227, Short.MAX_VALUE)
        );

        AccLabel4.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        AccLabel4.setText("Accelerometer");

        javax.swing.GroupLayout jPanel4Layout = new javax.swing.GroupLayout(jPanel4);
        jPanel4.setLayout(jPanel4Layout);
        jPanel4Layout.setHorizontalGroup(
            jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel4Layout.createSequentialGroup()
                .addComponent(Temp_RR, javax.swing.GroupLayout.PREFERRED_SIZE, 109, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel4Layout.createSequentialGroup()
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(Strain_RR, javax.swing.GroupLayout.PREFERRED_SIZE, 386, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(jPanel4Layout.createSequentialGroup()
                        .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel4Layout.createSequentialGroup()
                                .addGap(103, 103, 103)
                                .addComponent(AccLabel4))
                            .addComponent(jDesktopPane4, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                        .addGap(0, 0, 0)
                        .addComponent(AccZ_RR, javax.swing.GroupLayout.PREFERRED_SIZE, 130, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addGap(0, 0, Short.MAX_VALUE))
        );
        jPanel4Layout.setVerticalGroup(
            jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel4Layout.createSequentialGroup()
                .addGap(0, 0, Short.MAX_VALUE)
                .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel4Layout.createSequentialGroup()
                        .addGroup(jPanel4Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel4Layout.createSequentialGroup()
                                .addGap(25, 25, 25)
                                .addComponent(AccLabel4)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addComponent(jDesktopPane4, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                            .addGroup(jPanel4Layout.createSequentialGroup()
                                .addGap(0, 0, Short.MAX_VALUE)
                                .addComponent(AccZ_RR, javax.swing.GroupLayout.PREFERRED_SIZE, 288, javax.swing.GroupLayout.PREFERRED_SIZE)))
                        .addComponent(Strain_RR, javax.swing.GroupLayout.PREFERRED_SIZE, 116, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addComponent(Temp_RR, javax.swing.GroupLayout.PREFERRED_SIZE, 423, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(0, 0, Short.MAX_VALUE))
        );

        label4.setAlignment(java.awt.Label.CENTER);
        label4.setCursor(new java.awt.Cursor(java.awt.Cursor.DEFAULT_CURSOR));
        label4.setFont(new java.awt.Font("Dialog", 0, 18)); // NOI18N
        label4.setText("Rear Right");

        jButton1.setBackground(new java.awt.Color(153, 153, 153));
        jButton1.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        jButton1.setForeground(new java.awt.Color(204, 0, 0));
        jButton1.setText("Exit");
        jButton1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton1ActionPerformed(evt);
            }
        });

        TimeLabel2.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        TimeLabel2.setText("Date");

        jMenu1.setText("File");
        jMenuBar1.add(jMenu1);

        jMenu2.setText("Edit");
        jMenuBar1.add(jMenu2);

        setJMenuBar(jMenuBar1);

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGap(50, 50, 50)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(92, 92, 92)
                        .addComponent(jButton1)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                            .addComponent(jPanel2, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                            .addComponent(label3, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)))
                    .addGroup(layout.createSequentialGroup()
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(layout.createSequentialGroup()
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(RPMGauge, javax.swing.GroupLayout.PREFERRED_SIZE, 225, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addGroup(layout.createSequentialGroup()
                                        .addGap(35, 35, 35)
                                        .addComponent(startButton1)
                                        .addGap(40, 40, 40)
                                        .addComponent(stopButton2))
                                    .addComponent(jDateChooser2, javax.swing.GroupLayout.PREFERRED_SIZE, 154, javax.swing.GroupLayout.PREFERRED_SIZE))
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(jTextField2, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addGroup(layout.createSequentialGroup()
                                        .addGap(20, 20, 20)
                                        .addComponent(RunTimeLabel2))
                                    .addGroup(layout.createSequentialGroup()
                                        .addGap(29, 29, 29)
                                        .addComponent(TimeLabel2)))
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                    .addGroup(layout.createSequentialGroup()
                                        .addGap(68, 68, 68)
                                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                            .addComponent(jTextField4, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)
                                            .addGroup(layout.createSequentialGroup()
                                                .addGap(26, 26, 26)
                                                .addComponent(TestNoLabel3))
                                            .addGroup(layout.createSequentialGroup()
                                                .addGap(29, 29, 29)
                                                .addComponent(TimeLabel1))))
                                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                            .addComponent(jTextField3, javax.swing.GroupLayout.PREFERRED_SIZE, 100, javax.swing.GroupLayout.PREFERRED_SIZE)
                                            .addComponent(RoomTempLabel4))
                                        .addGap(66, 66, 66)))
                                .addGap(145, 145, 145)))
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                            .addComponent(jPanel1, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                            .addComponent(label1, javax.swing.GroupLayout.PREFERRED_SIZE, 508, javax.swing.GroupLayout.PREFERRED_SIZE))))
                .addGap(18, 18, 18)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                    .addComponent(jPanel3, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                    .addComponent(label2, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                    .addComponent(jPanel4, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                    .addComponent(label4, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(label2, javax.swing.GroupLayout.PREFERRED_SIZE, 38, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(0, 0, 0)
                        .addComponent(jPanel3, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(label1, javax.swing.GroupLayout.PREFERRED_SIZE, 38, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(0, 0, 0)
                        .addComponent(jPanel1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(label3, javax.swing.GroupLayout.PREFERRED_SIZE, 38, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(0, 0, 0)
                        .addComponent(jPanel2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(label4, javax.swing.GroupLayout.PREFERRED_SIZE, 38, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(0, 0, 0)
                        .addComponent(jPanel4, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addGap(0, 21, Short.MAX_VALUE))
            .addGroup(layout.createSequentialGroup()
                .addGap(136, 136, 136)
                .addComponent(RPMGauge, javax.swing.GroupLayout.PREFERRED_SIZE, 209, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGap(79, 79, 79)
                .addComponent(jDateChooser2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                    .addComponent(TimeLabel1)
                    .addComponent(TimeLabel2))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(jTextField2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(RunTimeLabel2))
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(jTextField4, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(TestNoLabel3)))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                .addComponent(jTextField3, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(RoomTempLabel4)
                .addGap(40, 40, 40)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(startButton1)
                    .addComponent(stopButton2))
                .addGap(33, 33, 33)
                .addComponent(jButton1)
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                        

    private void startButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                             
        // TODO add your handling code here:
    }                                            

    private void stopButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                            
        // TODO add your handling code here:
    }                                           

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        System.exit(0);
    }                                        

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(MainFrm.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(MainFrm.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(MainFrm.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(MainFrm.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new MainFrm().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JLabel AccLabel1;
    private javax.swing.JLabel AccLabel2;
    private javax.swing.JLabel AccLabel3;
    private javax.swing.JLabel AccLabel4;
    private eu.hansolo.steelseries.gauges.Linear AccZ_FL;
    private eu.hansolo.steelseries.gauges.Linear AccZ_FR;
    private eu.hansolo.steelseries.gauges.Linear AccZ_RL;
    private eu.hansolo.steelseries.gauges.Linear AccZ_RR;
    private eu.hansolo.steelseries.gauges.RadialBargraph RPMGauge;
    private javax.swing.JLabel RoomTempLabel4;
    private javax.swing.JLabel RunTimeLabel2;
    private eu.hansolo.steelseries.gauges.Linear Strain_FL;
    private eu.hansolo.steelseries.gauges.Linear Strain_FR;
    private eu.hansolo.steelseries.gauges.Linear Strain_RL;
    private eu.hansolo.steelseries.gauges.Linear Strain_RR;
    private eu.hansolo.steelseries.gauges.LinearBargraph Temp_FL;
    private eu.hansolo.steelseries.gauges.LinearBargraph Temp_FR;
    private eu.hansolo.steelseries.gauges.LinearBargraph Temp_RL;
    private eu.hansolo.steelseries.gauges.LinearBargraph Temp_RR;
    private javax.swing.JLabel TestNoLabel3;
    private javax.swing.JLabel TimeLabel1;
    private javax.swing.JLabel TimeLabel2;
    private javax.swing.JButton jButton1;
    private com.toedter.calendar.JDateChooser jDateChooser2;
    private javax.swing.JDesktopPane jDesktopPane1;
    private javax.swing.JDesktopPane jDesktopPane2;
    private javax.swing.JDesktopPane jDesktopPane3;
    private javax.swing.JDesktopPane jDesktopPane4;
    private javax.swing.JLabel jLabel11;
    private javax.swing.JLabel jLabel6;
    private javax.swing.JLabel jLabel7;
    private javax.swing.JLabel jLabel9;
    private javax.swing.JMenu jMenu1;
    private javax.swing.JMenu jMenu2;
    private javax.swing.JMenuBar jMenuBar1;
    private javax.swing.JPanel jPanel1;
    private javax.swing.JPanel jPanel2;
    private javax.swing.JPanel jPanel3;
    private javax.swing.JPanel jPanel4;
    private javax.swing.JScrollPane jScrollPane1;
    private javax.swing.JTextArea jTextArea1;
    private javax.swing.JTextField jTextField2;
    private javax.swing.JTextField jTextField3;
    private javax.swing.JTextField jTextField4;
    private java.awt.Label label1;
    private java.awt.Label label2;
    private java.awt.Label label3;
    private java.awt.Label label4;
    private org.pushingpixels.trident.ease.Linear linear2;
    private eu.hansolo.steelseries.gauges.LinearBargraphBeanInfo linearBargraphBeanInfo1;
    private java.awt.Menu menu1;
    private java.awt.Menu menu2;
    private java.awt.MenuBar menuBar1;
    private eu.hansolo.steelseries.gauges.RadialBargraphBeanInfo radialBargraphBeanInfo1;
    private javax.swing.JButton startButton1;
    private javax.swing.JButton stopButton2;
    // End of variables declaration                   
}

