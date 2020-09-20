RESUME
======  

Name and Surname
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Nastya Danilova

Contact Information
-------------------
Telephone number: +375(44)739-78-42;  

Email: nastya.danilova.9913@gmail.com;

Brief Information About Yourself
--------------------------------
Purpose: Visit different countries, taste different cuisines of the world;  

Priorities: financial well-being, self-realization, family, health;  

Strengths: honesty, conscientiousness, reliability, focus on results, discipline, punctuality, accuracy, love for detail, diligence, hard work;  

Work experienc: Now I am in my second year of university and want to get real experience in programming. I really want to grow and develop as a programmer, learn a lot of new and relevant information, and acquire useful skills.

Skills
------
Programming Languages: C#, Java, JavaScript, PHP, SQL, HTML, CSS;  

Version control systems: Git;

Sample Code
-----------
    using System;
    using System.Windows.Forms;
    namespace Policlinic
    {public partial class Form1 : Form{
    ToolStripLabel dateLabel;
    ToolStripLabel timeLabel;
    ToolStripLabel infoLabel;
    ToolStripLabel mouseLabel;
    Timer timer;
    public Form1(){
    InitializeComponent();
    mouseLabel = new ToolStripLabel();
    mouseLabel.Text = " ";
    infoLabel = new ToolStripLabel();
    infoLabel.Text = "Текущие дата и время:";
    dateLabel = new ToolStripLabel();
    timeLabel = new ToolStripLabel();
    statusStrip1.Items.Add(mouseLabel);
    statusStrip1.Items.Add(infoLabel);
    statusStrip1.Items.Add(dateLabel);
    statusStrip1.Items.Add(timeLabel);
    timer = new Timer() { Interval = 1000 };
    timer.Tick += timer_Tick;
    timer.Start();}
    public void timer_Tick(object sender, EventArgs e){
    dateLabel.Text = DateTime.Now.ToLongDateString();
    timeLabel.Text = DateTime.Now.ToLongTimeString();}
    private void nurses_B_Click(object sender, EventArgs e){
    Form2 form = new Form2();
    this.Hide();
    form.Show();}
    private void inspection_B_Click(object sender, EventArgs e){
    Form3 form = new Form3();
    this.Hide();
    form.Show();}
    private void salary_B_Click(object sender, EventArgs e){
    Form4 form = new Form4();
    this.Hide();
    form.Show();}
    private void holidays_B_Click(object sender, EventArgs e){
    Form5 form = new Form5();
    this.Hide();
    form.Show();}
    private void schedule_B_Click(object sender, EventArgs e){
    Form6 form = new Form6();
    this.Hide();
    form.Show();}
    private void waste_B_Click(object sender, EventArgs e){
    Form7 form = new Form7();
    this.Hide();
    form.Show();}
    private void выходToolStripMenuItem_Click(object sender, EventArgs e){
    if (MessageBox.Show(this, "Вы точно хотите выйти?", "Выход", MessageBoxButtons.OKCancel, MessageBoxIcon.Question, MessageBoxDefaultButton.Button2) == DialogResult.OK){
    Form1 form = new Form1();
    this.Close();
    Application.Exit();}}
    private void nurses_B_MouseEnter(object sender, EventArgs e){
    mouseLabel.Text = "Переход на форму Санитарки";}
    public void B_MouseLeave(object sender, EventArgs e){
    mouseLabel.Text = " ";}
    private void inspection_B_MouseEnter(object sender, EventArgs e){
    mouseLabel.Text = "Переход на форму Проф. осмотр";}
    private void salary_B_MouseEnter(object sender, EventArgs e){
    mouseLabel.Text = "Переход на форму Трудовой паспорт";}
    private void holidays_B_MouseEnter(object sender, EventArgs e){
    mouseLabel.Text = "Переход на форму Отпуска";}
    private void schedule_B_MouseEnter(object sender, EventArgs e){
    mouseLabel.Text = "Переход на форму График уборки";}
    private void waste_B_MouseEnter(object sender, EventArgs e){
    mouseLabel.Text = "Переход на форму Отходы";}
    private void санитаркиToolStripMenuItem_Click(object sender, EventArgs e){
    Form10 form = new Form10();
    this.Hide();
    form.Show();}
    private void профОсмотрToolStripMenuItem_Click(object sender, EventArgs e){
    string fPath = Application.StartupPath;
    string fileName = fPath + "\Help.chm";
    Help.ShowHelp(this, fileName);}}}

Education
---------
University: Belarusian State University of Informatics and Radioelectronics;  

Courses: Forsta (English), Language Training Center BSUIR (English);

English Language Proficiency
----------------------------
Intermediate(B1)
