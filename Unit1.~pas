unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, ExtCtrls, jpeg;

type
  TForm1 = class(TForm)
    Panel1: TPanel;
    Label1: TLabel;
    Label2: TLabel;
    Label3: TLabel;
    Button1: TButton;
    Button2: TButton;
    Edit1: TEdit;
    Edit2: TEdit;
    Image1: TImage;
    Label4: TLabel;
    procedure Button2Click(Sender: TObject);
    procedure Button1Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

uses Unit2;

{$R *.dfm}

procedure TForm1.Button2Click(Sender: TObject);
begin
Application.Terminate;
end;

procedure TForm1.Button1Click(Sender: TObject);
begin
if (edit1.Text='user') and (edit2.Text='password') then
begin
form1.Visible:=false;
form2.visible:=true;
MessageDlg('Anda berhasil login',mtInformation,[mbOK],0);
end else if (edit1.Text='') then
begin
MessageDlg('Usernya diisi dulu ya',mtError,[mbOK],0);
end else if (edit2.Text='') then
begin
MessageDlg('Passwordnya diisi dulu ya',mtError,[mbOK],0);
end else
MessageDlg('User / Password yg salah',mtError,[mbOK],0);
edit1.Text:='';
edit2.Text:='';
end;

end.
