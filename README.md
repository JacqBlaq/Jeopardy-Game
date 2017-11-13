# Jeopardy-Game
- I created a GUI Jeopardy game.
- The categories are popular movie series/ TV shows
- (Harry Potter, Star Wars, Game of Thrones, Lord of the Rings, Spongebob, Disney)
- This is a two player game and works the same way as Jeopardy.
### Requirements
- Preferred IDE: Eclipse (But use whatever youre comfortable with)

### Importing saved file into Eclipse
1. Open **Eclipse**
1. From main menu, select **File** > **Import**
1. Expand General folder, select **Existing Projects into Workspace** and click **Next**
1. If not zip file: Click **Select root directory**
1. If zip file: Click **Select archive directory**
1. Browse for file location
1. Click **Finish**
```
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JOptionPane;
import javax.swing.ImageIcon;
import javax.swing.JButton;
import javax.swing.JPanel;
import java.awt.Font;
import java.awt.GridLayout;
import java.awt.Image;
import java.awt.BorderLayout;
import java.awt.FlowLayout;
import java.awt.Color;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;
```
----
Main Menu | Rules| Player 1 name input
---- | ----- | ----
<img src="https://image.ibb.co/kCj73G/Jeopardy1.png" border="1" width="270px"> | <img src="https://image.ibb.co/cE7icb/Jeopardy2.png" border="1"> | <img src="https://image.ibb.co/m7HS3G/jeopardy3.png" alt="jeopardy3" border="0">

player 2 name input | Game Board | Question
---- | ----- | ----
<img src="https://image.ibb.co/cc4UHb/jeopardy4.png" border="1"> | <img src="https://image.ibb.co/nnQrVw/jeopardy5.png" alt="jeopardy5" border="1" width="250px"> | <img src="https://image.ibb.co/kmMyAw/jeopardy6.png" border="1" width="250px">

Correct Answer Message | Score gets added at bottom | Answer input
---- | ----- | ----
<img src="https://image.ibb.co/f2ddAw/jeopardy7.png" border="1"> | <img src="https://image.ibb.co/nz4wxb/jeopardy8.png" border="1"> | <img src="https://image.ibb.co/eHsS3G/jeopardy9.png" border="1">

