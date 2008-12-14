{
Copyright (c) 2008 Tristan Seifert<seiferttristan(at)gmail(dot)com>

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
}
unit Unit1; 

{$mode objfpc}{$H+}

interface

uses
  Classes, SysUtils, LResources, Forms, Controls, Graphics, Dialogs,
  SynHighlighterHTML, SynEdit, SynHighlighterPas, SynHighlighterCpp,
  SynHighlighterJava, SynHighlighterPerl, SynHighlighterXML, SynHighlighterLFM,
  synhighlighterunixshellscript, SynHighlighterCss, SynHighlighterTeX,
  SynHighlighterSQL, SynHighlighterPython, StdCtrls, ExtCtrls, Menus,
  SynHighlighterPHP, SynExportHTML, SynCompletion,
  SynHighlighterAny, Buttons, PrintersDlgs,Printers, ComCtrls,
  ActnList, ExtDlgs,RTTICtrls,Clipbrd,Types;

type

  { TForm1 }

  TForm1 = class(TForm)
    BitBtn1: TBitBtn;
    BitBtn2: TBitBtn;
    CalculatorDialog1: TCalculatorDialog;
    Cpp: TSynCppSyn;
    CSS: TSynCssSyn;
    HeaderControl1: THeaderControl;
    Image1: TImage;
    Image2: TImage;
    Image3: TImage;
    ImageList1: TImageList;
    ListBox1: TListBox;
    ListBox2: TListBox;
    ListBox3: TListBox;
    MainMenu1: TMainMenu;
    Memo1: TMemo;
    MenuItem1: TMenuItem;
    MenuItem10: TMenuItem;
    MenuItem11: TMenuItem;
    MenuItem12: TMenuItem;
    MenuItem13: TMenuItem;
    MenuItem14: TMenuItem;
    MenuItem15: TMenuItem;
    MenuItem16: TMenuItem;
    MenuItem17: TMenuItem;
    MenuItem18: TMenuItem;
    MenuItem19: TMenuItem;
    MenuItem2: TMenuItem;
    MenuItem20: TMenuItem;
    MenuItem21: TMenuItem;
    MenuItem22: TMenuItem;
    MenuItem23: TMenuItem;
    MenuItem24: TMenuItem;
    MenuItem25: TMenuItem;
    MenuItem26: TMenuItem;
    MenuItem27: TMenuItem;
    MenuItem28: TMenuItem;
    MenuItem29: TMenuItem;
    MenuItem3: TMenuItem;
    MenuItem30: TMenuItem;
    MenuItem31: TMenuItem;
    MenuItem32: TMenuItem;
    MenuItem4: TMenuItem;
    MenuItem5: TMenuItem;
    MenuItem6: TMenuItem;
    MenuItem7: TMenuItem;
    MenuItem8: TMenuItem;
    MenuItem9: TMenuItem;
    OpenDialog1: TOpenDialog;
    PageControl1: TPageControl;
    PopupMenu1: TPopupMenu;
    PrintDialog: TPrintDialog;
    PrinterSetupDialog1: TPrinterSetupDialog;
    ProgressBar1: TProgressBar;
    SaveDialog1: TSaveDialog;
    SaveDialog2: TSaveDialog;
    SpeedButton1: TSpeedButton;
    SpeedButton10: TSpeedButton;
    SpeedButton11: TSpeedButton;
    SpeedButton2: TSpeedButton;
    SpeedButton3: TSpeedButton;
    SpeedButton4: TSpeedButton;
    SpeedButton5: TSpeedButton;
    SpeedButton6: TSpeedButton;
    SpeedButton7: TSpeedButton;
    SpeedButton8: TSpeedButton;
    SpeedButton9: TSpeedButton;
    SynAutoComplete1: TSynAutoComplete;
    SynEdit1: TSynEdit;
    FPAS: TSynFreePascalSyn;//#
    HTML: TSynHTMLSyn;//#
    java: TSynJavaSyn;//#
    LFM: TSynLFMSyn;//#
    PAS: TSynPasSyn;//#
    Perl: TSynPerlSyn;//#
    Pyton: TSynPythonSyn;//#
    SQL: TSynSQLSyn;     //#
    PHP: TSynPHPSyn;
    Exporter: TSynExporterHTML;
    TabSheet1: TTabSheet;
    TabSheet2: TTabSheet;
    TabSheet3: TTabSheet;
    Tex: TSynTeXSyn;     //#
    SH: TSynUNIXShellScriptSyn;
    Timer1: TTimer;
    Timer2: TTimer;
    Timer3: TTimer;
    Timer4: TTimer;
    Timer5: TTimer;
    Timer6: TTimer;
    XML: TSynXMLSyn;

    procedure BitBtn1Click(Sender: TObject);
    procedure BitBtn2Click(Sender: TObject);
    procedure Button1Click(Sender: TObject);
    procedure FormClose(Sender: TObject; var CloseAction: TCloseAction);
    procedure FormCloseQuery(Sender: TObject; var CanClose: boolean);
    procedure FormCreate(Sender: TObject);
    procedure FormResize(Sender: TObject);
    procedure ListBox1DblClick(Sender: TObject);
    procedure ListBox2DblClick(Sender: TObject);
    procedure ListBox3DblClick(Sender: TObject);
    procedure MenuItem10Click(Sender: TObject);
    procedure MenuItem11Click(Sender: TObject);
    procedure MenuItem12Click(Sender: TObject);
    procedure MenuItem13Click(Sender: TObject);
    procedure MenuItem14Click(Sender: TObject);
    procedure MenuItem15Click(Sender: TObject);
    procedure MenuItem16Click(Sender: TObject);
    procedure MenuItem17Click(Sender: TObject);
    procedure MenuItem18Click(Sender: TObject);
    procedure MenuItem20Click(Sender: TObject);
    procedure MenuItem21Click(Sender: TObject);
    procedure MenuItem22Click(Sender: TObject);
    procedure MenuItem23Click(Sender: TObject);
    procedure MenuItem24Click(Sender: TObject);
    procedure MenuItem25Click(Sender: TObject);
    procedure MenuItem26Click(Sender: TObject);
    procedure MenuItem27Click(Sender: TObject);
    procedure MenuItem28Click(Sender: TObject);
    procedure MenuItem29Click(Sender: TObject);
    procedure MenuItem2Click(Sender: TObject);
    procedure MenuItem31Click(Sender: TObject);
    procedure MenuItem3Click(Sender: TObject);
    procedure MenuItem4Click(Sender: TObject);
    procedure MenuItem5Click(Sender: TObject);
    procedure MenuItem6Click(Sender: TObject);
    procedure MenuItem8Click(Sender: TObject);
    procedure MenuItem9Click(Sender: TObject);
    procedure PageControl1Change(Sender: TObject);
    procedure SpeedButton10Click(Sender: TObject);
    procedure SpeedButton11Click(Sender: TObject);
    procedure SpeedButton1Click(Sender: TObject);
    procedure SpeedButton2Click(Sender: TObject);
    procedure SpeedButton3Click(Sender: TObject);
    procedure SpeedButton4Click(Sender: TObject);
    procedure SpeedButton5Click(Sender: TObject);
    procedure SpeedButton6Click(Sender: TObject);
    procedure SpeedButton7Click(Sender: TObject);
    procedure SpeedButton8Click(Sender: TObject);
    procedure SpeedButton9Click(Sender: TObject);
    procedure SynEdit1Change(Sender: TObject);
    procedure SynEdit1KeyDown(Sender: TObject; var Key: Word; Shift: TShiftState
      );
    procedure Timer2Timer(Sender: TObject);
    procedure Timer3Timer(Sender: TObject);
    procedure Timer4Timer(Sender: TObject);
    procedure Timer5Timer(Sender: TObject);
    procedure Timer6Timer(Sender: TObject);
    procedure TimerTimer(Sender: TObject);
 //   procedure Slide(Sbegin:integer;SEnd:integer;Element:TObject);

  private
    { private declarations }
    procedure WMNCRButtonDown({var Msg: TWMNCRButtonDown}) ; {message WM_NCRBUTTONDOWN; }
  public
    { public declarations }
  end; 

var
  Form1: TForm1; 
  filen:string;
  new:Integer;
  code,wid,hei:integer;
  a:integer;
  fs,fsi:int64;

implementation

{ TForm1 }
procedure ScaleForm
    (F: TForm; ScreenWidth, ScreenHeight: LongInt) ;
begin
//   F.Scaled := True;
   F.AutoScroll := False;
   F.Position := poScreenCenter;
   F.Font.Name := 'swasdee';
   if (Screen.Width <> ScreenWidth) then begin
     F.Height :=
         LongInt(F.Height) * LongInt(Screen.Height)
         div ScreenHeight;
     F.Width :=
         LongInt(F.Width) * LongInt(Screen.Width)
         div ScreenWidth;
//     F.ScaleBy(Screen.Width,ScreenWidth) ;
   end;
end;


procedure TForm1.WMNCRButtonDown({var Msg: TWMNCRButtonDown}) ;
var
   h : integer;
   i : double;
begin
{   if (Msg.HitTest = HTCAPTION) then
   begin
     if (ClientHeight = 0) then
     begin
       for h := 0 to fOldClientHeight do ClientHeight := h;
       Application.ProcessMessages;
     end
     else
     begin }

     end;

function GetFileSize(const FileName: string): Int64;
var
  FileStream: TFileStream;
begin
  FileStream := TFileStream.Create(FileName, fmOpenRead or fmShareDenyNone);
  try
    try
      Result := FileStream.Size;
    except
      Result := 0;
    end;
  finally
    FileStream.Free;
  end;
end;

function slide():integer;
begin

 {    For i := 280 to -280 do
begin
    Element.Left:=Element.Left-1;
end;
}



end;




procedure TForm1.FormClose(Sender: TObject; var CloseAction: TCloseAction);

begin
if new=1 then
begin
SaveDialog1.Execute;
SynEdit1.Lines.SaveToFile(SaveDialog1.Filename);
close;
end;
if new=0 then
begin
 SynEdit1.Lines.SaveToFile(filen);
 close;
 end;

close;



end;

procedure TForm1.BitBtn2Click(Sender: TObject);
begin
  SynEdit1.Lines.LoadFromFile(filen);
          Memo1.Visible:=false;
          BitBtn2.Visible:=false;
          BitBtn1.Visible:=false;
  Timer5.Interval:=2000;
end;

procedure TForm1.Button1Click(Sender: TObject);
begin
  WMNCRButtonDown();
end;

procedure TForm1.BitBtn1Click(Sender: TObject);
begin
    Timer5.Interval:=2000;
    SynEdit1.Lines.SaveToFile(filen);
Memo1.Visible:=false;
          BitBtn2.Visible:=false;
          BitBtn1.Visible:=false;
end;

procedure TForm1.FormCloseQuery(Sender: TObject; var CanClose: boolean);
var
exec:integer;
begin
//MessageBeep(MB_ICONQUESTION);
Beep();
exec:=MessageDlg('TSEdit','Do you realy want to close?'+#13+'This could cause loss of unsaved Data.',mtConfirmation,[mbYes,mbNo,mbCancel],'');

if exec=2 then CanClose:=false;
if exec=7 then CanClose:=false;
if exec=6 then CanClose:=true;

end;


procedure TForm1.FormCreate(Sender: TObject);
begin
  new:=1;
  a:=0;
  hei:=Screen.Height;
  wid:=Screen.Width;

end;

procedure TForm1.FormResize(Sender: TObject);
begin
//  hei:=Screen.Height;
//  wid:=Screen.Width;
hei:=Form1.Height;
wid:=Form1.Width;
{

SpeedButton1.Width:=wid/0.020695364;

SpeedButton2.Width:=wid/0.020695364;

SpeedButton3.Width:=wid/0.020695364;

SpeedButton4.Width:=wid/0.020695364;

SpeedButton5.Width:=wid/0.020695364;

SpeedButton6.Width:=wid/0.020695364;

SpeedButton8.Width:=wid/0.020695364;

SpeedButton9.Width:=wid/0.020695364;
SpeedButton10.Width:=wid/0.020695364;
}
//ShowMessage(floattostr(wid-1081/2));

end;




procedure TForm1.ListBox1DblClick(Sender: TObject);
begin
  SynEdit1.Lines.Add(ListBox1.Items[ListBox1.ItemIndex]);
end;



procedure TForm1.ListBox2DblClick(Sender: TObject);
begin
    SynEdit1.Lines.Add(ListBox2.Items[ListBox2.ItemIndex]);
end;

procedure TForm1.ListBox3DblClick(Sender: TObject);
begin
    SynEdit1.Lines.Add(ListBox3.Items[ListBox3.ItemIndex]);
end;

procedure TForm1.MenuItem10Click(Sender: TObject);
begin
 SynEdit1.Highlighter:=java;

end;

procedure TForm1.MenuItem11Click(Sender: TObject);
begin
 SynEdit1.Highlighter:=LFM;

end;

procedure TForm1.MenuItem12Click(Sender: TObject);
begin

 SynEdit1.Highlighter:=Perl;
end;

procedure TForm1.MenuItem13Click(Sender: TObject);
begin

 SynEdit1.Highlighter:=PAS;
end;

procedure TForm1.MenuItem14Click(Sender: TObject);
begin

 SynEdit1.Highlighter:=Pyton;
end;

procedure TForm1.MenuItem15Click(Sender: TObject);
begin

 SynEdit1.Highlighter:=SQL;
end;

procedure TForm1.MenuItem16Click(Sender: TObject);
begin

 SynEdit1.Highlighter:=Tex;
end;

procedure TForm1.MenuItem17Click(Sender: TObject);
begin

 SynEdit1.Highlighter:=XML;
end;

procedure TForm1.MenuItem18Click(Sender: TObject);
begin

 SynEdit1.Highlighter:=SH;
end;

procedure TForm1.MenuItem20Click(Sender: TObject);
begin
  SynEdit1.Undo;
end;

procedure TForm1.MenuItem21Click(Sender: TObject);
begin
  SynEdit1.Redo;

end;

procedure TForm1.MenuItem22Click(Sender: TObject);
begin
  SynEdit1.Highlighter:=PHP;
end;

procedure TForm1.MenuItem23Click(Sender: TObject);
begin
Exporter.Highlighter:=SynEdit1.Highlighter;
Exporter.ExportAll(SynEdit1.Lines);
SaveDialog2.Execute;
Exporter.SaveToFile(SaveDialog2.Filename);
  Timer3.Enabled:=true;
  HeaderControl1.Visible:=true;
  HeaderControl1.Sections[0].Text:='Exporting...';
end;

procedure TForm1.MenuItem24Click(Sender: TObject);
begin
  if Code=0 then Timer1.Enabled:=true;
    if Code=1 then Timer2.Enabled:=true;
end;

procedure TForm1.MenuItem25Click(Sender: TObject);
begin
SynEdit1.CopyToClipboard;
end;

procedure TForm1.MenuItem26Click(Sender: TObject);
begin
  SynEdit1.PasteFromClipboard;
end;

procedure TForm1.MenuItem27Click(Sender: TObject);
begin
  SynEdit1.CutToClipboard;
end;

procedure TForm1.MenuItem28Click(Sender: TObject);
begin

end;

procedure TForm1.MenuItem29Click(Sender: TObject);
begin

end;

procedure TForm1.MenuItem2Click(Sender: TObject);
begin
  OpenDialog1.Execute;
  filen:=OpenDialog1.FileName;
    Caption:='TSEdit--'+filen;
end;

procedure TForm1.MenuItem31Click(Sender: TObject);
begin

end;

procedure TForm1.MenuItem3Click(Sender: TObject);

  VAR DruckDatei,
      TextDatei : TextFile;
      TextZeile : STRING;
begin

  IF PrintDialog.Execute
     THEN BEGIN
     Timer4.Enabled:=true;
           AssignFile (DruckDatei,'/tmp/TSEdit_print');
          Rewrite (DruckDatei);
          AssignFile (TextDatei,filen);
          Reset (TextDatei);
  Timer3.Enabled:=true;
  HeaderControl1.Visible:=true;
  HeaderControl1.Sections[0].Text:='Printing...';
          WHILE NOT EOF (TextDatei) DO BEGIN
                readln (TextDatei, TextZeile);
                writeln (DruckDatei, TextZeile);
                END;
          CloseFile (TextDatei);
          CloseFile (DruckDatei);
          END;
end;

procedure TForm1.MenuItem4Click(Sender: TObject);
begin
  SaveDialog1.Execute;
  filen:=SaveDialog1.FileName;
  SynEdit1.Lines.SaveToFile(filen);
    Caption:='TSEdit--'+filen;
end;

procedure TForm1.MenuItem5Click(Sender: TObject);
begin
  if new=1 then
  begin
  SaveDialog1.Execute;
  filen:=SaveDialog1.FileName;
  SynEdit1.Lines.SaveToFile(filen);
  new:=0;
    Timer3.Enabled:=true;
  HeaderControl1.Visible:=true;
  HeaderControl1.Sections[0].Text:='Saving...';
  end;
  Timer4.Enabled:=true;
Timer3.Enabled:=true;
  if new=0 then SynEdit1.Lines.SaveToFile(filen);
    Caption:='TSEdit--'+filen;
end;

procedure TForm1.MenuItem6Click(Sender: TObject);
begin
  new:=1;
end;

procedure TForm1.MenuItem8Click(Sender: TObject);
begin
 SynEdit1.Highlighter:=HTML;
end;

procedure TForm1.MenuItem9Click(Sender: TObject);
begin
 SynEdit1.Highlighter:=FPAS;

end;

procedure TForm1.PageControl1Change(Sender: TObject);
begin

end;

procedure TForm1.SpeedButton10Click(Sender: TObject);
begin
  //Form2.ShowModal;
end;

procedure TForm1.SpeedButton11Click(Sender: TObject);
begin
 ShowMessage('TSEdit v0.0.1');
end;

procedure TForm1.SpeedButton1Click(Sender: TObject);
begin
  Timer5.Enabled:=false;
  Timer5.Interval:=5000;
    if new=1 then
  begin
  SaveDialog1.Execute;
  filen:=SaveDialog1.FileName;
  SynEdit1.Lines.SaveToFile(filen);
  new:=0;
         fsi:=GetFileSize(filen);

      end;
      Timer4.Enabled:=true;
Timer3.Enabled:=true;
  if new=0 then SynEdit1.Lines.SaveToFile(filen);
    Caption:='TSEdit--'+filen;
      Timer3.Enabled:=true;
  HeaderControl1.Visible:=true;
  HeaderControl1.Sections[0].Text:='Saving...';
end;

procedure TForm1.SpeedButton2Click(Sender: TObject);
begin
  new:=1;
    Caption:='TSEdit--New File1';
    Timer4.Enabled:=true;
    Timer3.Enabled:=true;
end;

procedure TForm1.SpeedButton3Click(Sender: TObject);
var exec:integer;
begin

  OpenDialog1.Execute;
  Timer4.Enabled:=true;
Timer3.Enabled:=true;
  filen:=OpenDialog1.FileName;
  if GetFileSize(filen) >10240000{mehr als 10MB groß} then
  begin
 exec:= MessageDlg('Warning!','This file is too big.'+#13+'It is more then 10 MB in size.This could slow down your computer in speed.'+#13+'Do you want to Continue?',mtWarning,[mbYes,mbNo],'');
 if exec=6 then   SynEdit1.Lines.LoadFromFile(filen);
   end;
   if GetFileSize(filen) < 10240000 then SynEdit1.Lines.LoadFromFile(filen);
  Caption:='TSEdit--'+filen;
  new:=0;
       fs:=GetFileSize(filen);
       fsi:=GetFileSize(filen);

end;

procedure TForm1.SpeedButton4Click(Sender: TObject);
VAR DruckDatei,
      TextDatei : TextFile;
      TextZeile : STRING;
      dlgExec:integer;
begin
Timer4.Enabled:=true;
dlgExec:= MessageDlg('Print','Do you want to set a Border and the Layout?',mtConfirmation,[mbYes,MbNo],'');
if dlgExec = 6 then PrinterSetupDialog1.Execute;

  IF PrintDialog.Execute
     THEN BEGIN
               AssignFile (DruckDatei,'/tmp/TSEdit_print');
          Rewrite (DruckDatei);
          AssignFile (TextDatei,filen);
          Reset (TextDatei);
  Timer3.Enabled:=true;
  HeaderControl1.Visible:=true;
  HeaderControl1.Sections[0].Text:='Printing...';

          WHILE NOT EOF (TextDatei) DO BEGIN
                readln (TextDatei, TextZeile);
                writeln (DruckDatei, TextZeile);

                END;
          CloseFile (TextDatei);
          CloseFile (DruckDatei);
          END;

end;

procedure TForm1.SpeedButton5Click(Sender: TObject);
begin
Timer4.Enabled:=true;
  Exporter.Highlighter:=SynEdit1.Highlighter;
Exporter.ExportAll(SynEdit1.Lines);
SaveDialog2.Execute;
Exporter.SaveToFile(SaveDialog2.Filename);
  Timer3.Enabled:=true;
  HeaderControl1.Visible:=true;
  HeaderControl1.Sections[0].Text:='Exporting...';
end;

procedure TForm1.SpeedButton6Click(Sender: TObject);
begin
  SynEdit1.Highlighter:=nil;
end;

procedure TForm1.SpeedButton7Click(Sender: TObject);
begin
  Timer1.Enabled:=true;
        SpeedButton7.Visible:=false;
end;

procedure TForm1.SpeedButton8Click(Sender: TObject);
begin
close;

end;

procedure TForm1.SpeedButton9Click(Sender: TObject);
begin
  CalculatorDialog1.Execute;
  
end;

procedure TForm1.SynEdit1Change(Sender: TObject);
begin
if new=0 then
begin
ProgressBar1.BarShowText:=true;
ProgressBar1.Position:=fsi;
fs:=GetFileSize(filen)

end;

end;

procedure TForm1.SynEdit1KeyDown(Sender: TObject; var Key: Word;
  Shift: TShiftState);
begin
//  ShowMessage(inttostr(fsi)+''+#13+''+inttostr(fsi+1));
end;

procedure TForm1.Timer2Timer(Sender: TObject);
begin
        PageControl1.Left:=PageControl1.Left+5;
      SpeedButton7.Left:=SpeedButton7.Left+5;
      Timer2.Interval:=35;
      if PageControl1.Left= 0 then
      begin

      SpeedButton7.Visible:=false;
      Timer2.Enabled:=false;
            SpeedButton7.Visible:=true;

      end;
      Code:=0;
end;

procedure TForm1.Timer3Timer(Sender: TObject);
begin
  HeaderControl1.Visible:=false;
       fs:=GetFileSize(filen);
  Timer3.Enabled:=FALSE;
  Timer3.Interval:=5000;
  Timer4.Enabled:=false;
  Image3.Visible:=false;
  Image2.Visible:=false;
  Image1.Visible:=false;
  Timer5.Enabled:=true;
  

end;

procedure TForm1.Timer4Timer(Sender: TObject);
begin
  Timer4.Interval:=250;
  a:=a+1;
  
  if a=4 then
  begin
  a:=0;
  Image1.Visible:=false;
    Image2.Visible:=false;
      Image3.Visible:=false;
  end;
  
  if a=1 then
  begin
    Image1.Visible:=true;
        Image2.Visible:=false;
      Image3.Visible:=false;

  end;
  
  
    if a=2 then
  begin
    Image2.Visible:=true;
        Image1.Visible:=false;
      Image3.Visible:=false;

  end;
  
  
    if a=3 then
  begin
    Image1.Visible:=false;
    Image2.Visible:=false;
    Image3.Visible:=true;

  end;
end;

procedure TForm1.Timer5Timer(Sender: TObject);
begin
if new=0 then
begin
     if fs < GetFileSize(filen) then
     begin
          Memo1.Visible:=true;
          BitBtn1.Visible:=true;
          BitBtn2.Visible:=true;
          Memo1.Clear;
          Memo1.Lines.Add('The file »'+filen+'« has changed.');
          Memo1.Lines.Add('What do you want to do now?');
     end;
     if fs > GetFileSize(filen) then
     begin
          Memo1.Visible:=true;
          BitBtn1.Visible:=true;
          BitBtn2.Visible:=true;
          Memo1.Clear;
          Memo1.Lines.Add('The file »'+filen+'« has changed.');
          Memo1.Lines.Add('What do you want to do now?');

     end;
     fs:=GetFileSize(filen);
     Timer5.Interval:=2000;
end;
end;

procedure TForm1.Timer6Timer(Sender: TObject);
begin
  if new=1 then
  begin
  SaveDialog1.Execute;
  filen:=SaveDialog1.FileName;
  SynEdit1.Lines.SaveToFile(filen);
  new:=0;
  end;
  if new=0 then SynEdit1.Lines.SaveToFile(filen);
  Timer6.Interval:=30000;
end;


procedure TForm1.TimerTimer(Sender: TObject);
begin
      PageControl1.Left:=PageControl1.Left-5;

      //PageControl1.Top:=PageControl1.Top+5;
      SpeedButton7.Left:=SpeedButton7.Left-5;
      Timer1.Interval:=35;
      if PageControl1.Left= -290 then
      begin
      
      Timer1.Enabled:=false;
      
      end;
      Code:=1;
end;


initialization
  {$I unit1.lrs}

end.

