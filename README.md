# Base-de-datos-Colegio
// Main class
package MostrarFormlario;

import Ventana.FormularioVentana;

public class MainClass {
    public static void main(String[] args){
        FormularioVentana FV = new FormularioVentana();
        FV.setVisible(true);
    }
}

// Toda la parte de la interfaz
package Ventana;


import logica.alumno;
import logica.profesor;
import logica.Examen;
import logica.Practica;
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/GUIForms/JFrame.java to edit this template
 */

/**
 *
 * @author soloj
 */
public class FormularioVentana extends javax.swing.JFrame {
    
    private alumno CP;
    private profesor PF;
    private Examen EX;
    private Practica PA;
    /**
     * Creates new form NewJFrame
     */
    public FormularioVentana() {
        initComponents();
        CP = new alumno();
        PF = new profesor();
        EX = new Examen();
        PA = new Practica();
    }

    /**
     * This method is called from within the constructor to initialize the form.
     * WARNING: Do NOT modify this code. The content of this method is always
     * regenerated by the Form Editor.
     */
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        jPanel1 = new javax.swing.JPanel();
        jLabel1 = new javax.swing.JLabel();
        jLabel2 = new javax.swing.JLabel();
        jLabel3 = new javax.swing.JLabel();
        IDAlumno = new javax.swing.JTextField();
        jLabel4 = new javax.swing.JLabel();
        NombreAlumno = new javax.swing.JTextField();
        jLabel5 = new javax.swing.JLabel();
        ApellidoAlumno = new javax.swing.JTextField();
        jLabel6 = new javax.swing.JLabel();
        GrupoAlumno = new javax.swing.JTextField();
        GuardarAlumno = new javax.swing.JButton();
        jLabel7 = new javax.swing.JLabel();
        profesorID = new javax.swing.JTextField();
        jLabel8 = new javax.swing.JLabel();
        profesorNombre = new javax.swing.JTextField();
        jLabel9 = new javax.swing.JLabel();
        jLabel10 = new javax.swing.JLabel();
        profesorApellido = new javax.swing.JTextField();
        ProfesorBoton = new javax.swing.JButton();
        jLabel11 = new javax.swing.JLabel();
        jLabel12 = new javax.swing.JLabel();
        jLabel13 = new javax.swing.JLabel();
        jLabel14 = new javax.swing.JLabel();
        jLabel15 = new javax.swing.JLabel();
        examenId = new javax.swing.JTextField();
        examenTitulo = new javax.swing.JTextField();
        preguntasExamen = new javax.swing.JTextField();
        examenFecha = new javax.swing.JTextField();
        GuardarExamen = new javax.swing.JButton();
        jLabel16 = new javax.swing.JLabel();
        IdPractica = new javax.swing.JTextField();
        jLabel17 = new javax.swing.JLabel();
        jLabel18 = new javax.swing.JLabel();
        jLabel19 = new javax.swing.JLabel();
        jLabel20 = new javax.swing.JLabel();
        TituloPractica = new javax.swing.JTextField();
        jLabel21 = new javax.swing.JLabel();
        DificultadPractica = new javax.swing.JTextField();
        FechaPractica = new javax.swing.JTextField();
        NotaPractica = new javax.swing.JTextField();
        GuardarPractica = new javax.swing.JButton();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        jLabel1.setBackground(new java.awt.Color(255, 0, 0));
        jLabel1.setFont(new java.awt.Font("Times New Roman", 1, 24)); // NOI18N
        jLabel1.setForeground(new java.awt.Color(0, 0, 255));
        jLabel1.setHorizontalAlignment(javax.swing.SwingConstants.CENTER);
        jLabel1.setText("Formulario de profesores y estudiantes");

        jLabel2.setText("Alumno");

        jLabel3.setText("ID");

        IDAlumno.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                IDAlumnoActionPerformed(evt);
            }
        });

        jLabel4.setText("Nombre");

        NombreAlumno.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                NombreAlumnoActionPerformed(evt);
            }
        });

        jLabel5.setText("Apellido");

        ApellidoAlumno.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                ApellidoAlumnoActionPerformed(evt);
            }
        });

        jLabel6.setText("Grupo");

        GuardarAlumno.setText("Guardar alumno");
        GuardarAlumno.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                GuardarAlumnoActionPerformed(evt);
            }
        });

        jLabel7.setText("Profesor");

        jLabel8.setText("ID");

        jLabel9.setText("Nombre");

        jLabel10.setText("Apellido");

        ProfesorBoton.setText("Guardar profesor");
        ProfesorBoton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                ProfesorBotonActionPerformed(evt);
            }
        });

        jLabel11.setText("Examen teorico");

        jLabel12.setText("ID");

        jLabel13.setText("Titulo");

        jLabel14.setText("Numero de preguntas");

        jLabel15.setText("Fecha de realizacion");

        GuardarExamen.setText("Guardar examen teorico");
        GuardarExamen.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                GuardarExamenActionPerformed(evt);
            }
        });

        jLabel16.setText("ID");

        jLabel17.setText("Practica");

        jLabel18.setText("Titulo");

        jLabel19.setText("Grado de dificultad");

        jLabel20.setText("Fecha de realizacion");

        jLabel21.setText("Nota");

        GuardarPractica.setText("Guardar practica");
        GuardarPractica.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                GuardarPracticaActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout jPanel1Layout = new javax.swing.GroupLayout(jPanel1);
        jPanel1.setLayout(jPanel1Layout);
        jPanel1Layout.setHorizontalGroup(
            jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addComponent(jLabel1, javax.swing.GroupLayout.Alignment.TRAILING, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel1Layout.createSequentialGroup()
                .addContainerGap()
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                    .addGroup(jPanel1Layout.createSequentialGroup()
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jLabel4)
                            .addComponent(jLabel3)
                            .addComponent(jLabel5)
                            .addComponent(jLabel6))
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel1Layout.createSequentialGroup()
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(jLabel2)
                                    .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                        .addComponent(ApellidoAlumno, javax.swing.GroupLayout.DEFAULT_SIZE, 115, Short.MAX_VALUE)
                                        .addComponent(NombreAlumno)
                                        .addComponent(IDAlumno))))
                            .addGroup(jPanel1Layout.createSequentialGroup()
                                .addGap(11, 11, 11)
                                .addComponent(GrupoAlumno, javax.swing.GroupLayout.PREFERRED_SIZE, 115, javax.swing.GroupLayout.PREFERRED_SIZE))))
                    .addComponent(GuardarAlumno))
                .addGap(28, 28, 28)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel1Layout.createSequentialGroup()
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jLabel9)
                            .addComponent(jLabel8))
                        .addGap(18, 18, 18)
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                            .addComponent(jLabel7)
                            .addComponent(profesorNombre, javax.swing.GroupLayout.DEFAULT_SIZE, 113, Short.MAX_VALUE)
                            .addComponent(profesorID))
                        .addGap(18, 18, 18)
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jLabel13)
                            .addComponent(jLabel12)))
                    .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                        .addComponent(GuardarExamen)
                        .addGroup(jPanel1Layout.createSequentialGroup()
                            .addComponent(jLabel10)
                            .addGap(18, 18, 18)
                            .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                .addComponent(ProfesorBoton, javax.swing.GroupLayout.Alignment.TRAILING)
                                .addGroup(jPanel1Layout.createSequentialGroup()
                                    .addComponent(profesorApellido)
                                    .addGap(6, 6, 6)))
                            .addGap(12, 12, 12)
                            .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                .addComponent(jLabel14)
                                .addComponent(jLabel15))
                            .addGap(18, 18, 18)
                            .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                .addComponent(preguntasExamen, javax.swing.GroupLayout.DEFAULT_SIZE, 113, Short.MAX_VALUE)
                                .addComponent(examenFecha)
                                .addComponent(examenTitulo)
                                .addComponent(jLabel11)
                                .addComponent(examenId))
                            .addGap(42, 42, 42))))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                    .addComponent(jLabel18)
                    .addGroup(jPanel1Layout.createSequentialGroup()
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jLabel20)
                            .addComponent(jLabel21))
                        .addGap(13, 13, 13)
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel1Layout.createSequentialGroup()
                                .addComponent(GuardarPractica)
                                .addGap(0, 0, Short.MAX_VALUE))
                            .addGroup(jPanel1Layout.createSequentialGroup()
                                .addGap(4, 4, 4)
                                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(NotaPractica, javax.swing.GroupLayout.Alignment.TRAILING)
                                    .addComponent(FechaPractica)))))
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, jPanel1Layout.createSequentialGroup()
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jLabel16)
                            .addComponent(jLabel19))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                            .addComponent(DificultadPractica, javax.swing.GroupLayout.DEFAULT_SIZE, 113, Short.MAX_VALUE)
                            .addComponent(jLabel17)
                            .addComponent(TituloPractica)
                            .addComponent(IdPractica))))
                .addGap(27, 27, 27))
        );
        jPanel1Layout.setVerticalGroup(
            jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(jPanel1Layout.createSequentialGroup()
                .addComponent(jLabel1, javax.swing.GroupLayout.PREFERRED_SIZE, 49, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGap(18, 18, 18)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel2)
                    .addComponent(jLabel7)
                    .addComponent(jLabel11)
                    .addComponent(jLabel17))
                .addGap(18, 18, 18)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(IDAlumno, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel3)
                    .addComponent(profesorID, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel8)
                    .addComponent(jLabel12)
                    .addComponent(examenId, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel16)
                    .addComponent(IdPractica, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(18, 18, 18)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(NombreAlumno, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel4)
                    .addComponent(profesorNombre, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel9)
                    .addComponent(jLabel13)
                    .addComponent(examenTitulo, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel18)
                    .addComponent(TituloPractica, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(18, 18, 18)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(ApellidoAlumno, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel5)
                    .addComponent(jLabel10)
                    .addComponent(profesorApellido, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel14)
                    .addComponent(preguntasExamen, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel19)
                    .addComponent(DificultadPractica, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(18, 18, 18)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(GrupoAlumno, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel6)
                    .addComponent(jLabel15)
                    .addComponent(examenFecha, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel20)
                    .addComponent(FechaPractica, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(18, 18, 18)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel21)
                    .addComponent(NotaPractica, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(21, 21, 21)
                .addGroup(jPanel1Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(GuardarAlumno)
                    .addComponent(ProfesorBoton)
                    .addComponent(GuardarExamen)
                    .addComponent(GuardarPractica))
                .addGap(0, 46, Short.MAX_VALUE))
        );

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addComponent(jPanel1, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addComponent(jPanel1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGap(0, 0, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                        

    private void IDAlumnoActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
    }                                        

    private void NombreAlumnoActionPerformed(java.awt.event.ActionEvent evt) {                                             
        // TODO add your handling code here:
    }                                            

    private void ApellidoAlumnoActionPerformed(java.awt.event.ActionEvent evt) {                                               
        // TODO add your handling code here:
    }                                              

    private void ProfesorBotonActionPerformed(java.awt.event.ActionEvent evt) {                                              
        // TODO add your handling code here:
        int Nif = Integer.parseInt(profesorID.getText());
        String Nombre = profesorNombre.getText();
        String Apellidos = profesorApellido.getText();
        PF.insertarDatos(Nif, Nombre, Apellidos);
    }                                             

    private void GuardarAlumnoActionPerformed(java.awt.event.ActionEvent evt) {                                              
        // TODO add your handling code here:
        int Nif = Integer.parseInt(IDAlumno.getText());
        String Nombre = NombreAlumno.getText();
        String Apellidos = ApellidoAlumno.getText();
        String Grupo = GrupoAlumno.getText();
        CP.insertarDatos(Nif, Nombre, Apellidos, Grupo);
    }                                             

    private void GuardarExamenActionPerformed(java.awt.event.ActionEvent evt) {                                              
        // TODO add your handling code here:
        int Nif = Integer.parseInt(examenId.getText());
        String Titulo = examenTitulo.getText();
        int NumeroDePreguntas = Integer.parseInt(preguntasExamen.getText());
        String FechaDeRealizacion = examenFecha.getText();
        EX.insertarDatos(Nif, Titulo, NumeroDePreguntas, FechaDeRealizacion);
    }                                             

    private void GuardarPracticaActionPerformed(java.awt.event.ActionEvent evt) {                                                
        // TODO add your handling code here:
        int Nif = Integer.parseInt(IdPractica.getText());
        String Titulo = TituloPractica.getText();
        String FechaDeRealizacion = FechaPractica.getText();
        String GradoDeDificultad = DificultadPractica.getText();
        CP.insertarDatos(Nif, Titulo, FechaDeRealizacion, GradoDeDificultad);
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
            java.util.logging.Logger.getLogger(FormularioVentana.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(FormularioVentana.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(FormularioVentana.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(FormularioVentana.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new FormularioVentana().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JTextField ApellidoAlumno;
    private javax.swing.JTextField DificultadPractica;
    private javax.swing.JTextField FechaPractica;
    private javax.swing.JTextField GrupoAlumno;
    private javax.swing.JButton GuardarAlumno;
    private javax.swing.JButton GuardarExamen;
    private javax.swing.JButton GuardarPractica;
    private javax.swing.JTextField IDAlumno;
    private javax.swing.JTextField IdPractica;
    private javax.swing.JTextField NombreAlumno;
    private javax.swing.JTextField NotaPractica;
    private javax.swing.JButton ProfesorBoton;
    private javax.swing.JTextField TituloPractica;
    private javax.swing.JTextField examenFecha;
    private javax.swing.JTextField examenId;
    private javax.swing.JTextField examenTitulo;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel jLabel10;
    private javax.swing.JLabel jLabel11;
    private javax.swing.JLabel jLabel12;
    private javax.swing.JLabel jLabel13;
    private javax.swing.JLabel jLabel14;
    private javax.swing.JLabel jLabel15;
    private javax.swing.JLabel jLabel16;
    private javax.swing.JLabel jLabel17;
    private javax.swing.JLabel jLabel18;
    private javax.swing.JLabel jLabel19;
    private javax.swing.JLabel jLabel2;
    private javax.swing.JLabel jLabel20;
    private javax.swing.JLabel jLabel21;
    private javax.swing.JLabel jLabel3;
    private javax.swing.JLabel jLabel4;
    private javax.swing.JLabel jLabel5;
    private javax.swing.JLabel jLabel6;
    private javax.swing.JLabel jLabel7;
    private javax.swing.JLabel jLabel8;
    private javax.swing.JLabel jLabel9;
    private javax.swing.JPanel jPanel1;
    private javax.swing.JTextField preguntasExamen;
    private javax.swing.JTextField profesorApellido;
    private javax.swing.JTextField profesorID;
    private javax.swing.JTextField profesorNombre;
    // End of variables declaration                   
}

// Conexion con SQL en el cual se guardara la informacion de la base
package conexion;
import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.SQLException;
import javax.swing.JOptionPane;

public class conexion {
    
    private Connection cn;
    private static final String driver = "com.mysql.cj.jdbc.Driver";
    private static final String user = "root";
    private static final String password = "";
    private static final String url = "jdbc:mysql://localhost:3306/formulario?autoReconnect=true&useSSL=false";

    public conexion() {
        cn = null;
    }
    
    public Connection getConnection(){
        try{
            Class.forName (driver);
            cn = DriverManager.getConnection(url, user, password);
        }catch (ClassNotFoundException | SQLException ex){
            JOptionPane.showMessageDialog(null, ex.getMessage(), "Error al conectar la base de datos", JOptionPane.ERROR_MESSAGE);
            System.exit(0);
        }
        return cn;
    }
    
    public void close(){
        try{
            cn.close();
        } catch (SQLException ex) {
            JOptionPane.showMessageDialog(null, ex.getMessage(), "Error al cerrar la base de datos", JOptionPane.ERROR_MESSAGE);
        }
    }
}

//Lectura del alumno

package logica;

import conexion.conexion;
import java.sql.PreparedStatement;
import java.sql.SQLException;
import javax.swing.JOptionPane;

public class alumno {
    private final String SQLInsertar = "INSERT INTO alumno (Nif,Nombre,Apellidos,Grupo) values(?,?,?,?)";
    private PreparedStatement PS;
    private final conexion CN;
    
    public alumno (){
        PS = null;
        CN = new conexion();
    }
    
    public int insertarDatos(int Nif, String Nombre, String Apellidos, String Grupo){
        try{
            PS = CN.getConnection().prepareStatement(SQLInsertar);
            PS.setInt(1, Nif);
            PS.setString(2, Nombre);
            PS.setString(3, Apellidos);
            PS.setString(4, Grupo);
            int res=PS.executeUpdate();
            if(res > 0){
                JOptionPane.showMessageDialog(null, "Registro Guardado..");
            }
        } catch (SQLException e){
            System.err.println("Error al guardar los datos en la base: " + e.getMessage());
        }finally{
            PS = null;
            CN.close();
        }
        return 0;
    }
}

//Lectura del Profesor 
package logica;

import conexion.conexion;
import java.sql.PreparedStatement;
import java.sql.SQLException;
import javax.swing.JOptionPane;

public class alumno {
    private final String SQLInsertar = "INSERT INTO alumno (Nif,Nombre,Apellidos,Grupo) values(?,?,?,?)";
    private PreparedStatement PS;
    private final conexion CN;
    
    public alumno (){
        PS = null;
        CN = new conexion();
    }
    
    public int insertarDatos(int Nif, String Nombre, String Apellidos, String Grupo){
        try{
            PS = CN.getConnection().prepareStatement(SQLInsertar);
            PS.setInt(1, Nif);
            PS.setString(2, Nombre);
            PS.setString(3, Apellidos);
            PS.setString(4, Grupo);
            int res=PS.executeUpdate();
            if(res > 0){
                JOptionPane.showMessageDialog(null, "Registro Guardado..");
            }
        } catch (SQLException e){
            System.err.println("Error al guardar los datos en la base: " + e.getMessage());
        }finally{
            PS = null;
            CN.close();
        }
        return 0;
    }
}

//Lectura de un examen

package logica;

import conexion.conexion;
import java.sql.PreparedStatement;
import java.sql.SQLException;
import javax.swing.JOptionPane;

public class Examen {
    private final String SQLInsertar = "INSERT INTO alumno (Nif,Titulo,NumeroDePreguntas,FechaDeRealizacion) values(?,?,?,?)";
    private PreparedStatement PS;
    private final conexion CN;
    
    public Examen (){
        PS = null;
        CN = new conexion();
    }
    
    public int insertarDatos(int Nif, String Titulo, int NumeroDePreguntas, String FechaDeRealizacion){
        try{
            PS = CN.getConnection().prepareStatement(SQLInsertar);
            PS.setInt(1, Nif);
            PS.setString(2, Titulo);
            PS.setInt(3, NumeroDePreguntas);
            PS.setString(4, FechaDeRealizacion);
            int res=PS.executeUpdate();
            if(res > 0){
                JOptionPane.showMessageDialog(null, "Registro Guardado..");
            }
        } catch (SQLException e){
            System.err.println("Error al guardar los datos en la base: " + e.getMessage());
        }finally{
            PS = null;
            CN.close();
        }
        return 0;
    }
}

//Resultado de la prueba

package logica;

import conexion.conexion;
import java.sql.PreparedStatement;
import java.sql.SQLException;
import javax.swing.JOptionPane;

public class Practica {
    private final String SQLInsertar = "INSERT INTO practica (Nif,Nota,FechaDeRealizacion,GradoDeDificultad,Titulo) values(?,?,?,?,?)";
    private PreparedStatement PS;
    private final conexion CN;
    
    public Practica (){
        PS = null;
        CN = new conexion();
    }
    
    public int insertarDatos(int Nif, String Nota, String FechaDeRealizacion, String GradoDeDificultad, String Titulo){
        try{
            PS = CN.getConnection().prepareStatement(SQLInsertar);
            PS.setInt(1, Nif);
            PS.setString(2, Nota);
            PS.setString(3, FechaDeRealizacion);
            PS.setString(4, GradoDeDificultad);
            PS.setString(5, Titulo);
            int res=PS.executeUpdate();
            if(res > 0){
                JOptionPane.showMessageDialog(null, "Registro Guardado..");
            }
        } catch (SQLException e){
            System.err.println("Error al guardar los datos en la base: " + e.getMessage());
        }finally{
            PS = null;
            CN.close();
        }
        return 0;
    }
}
