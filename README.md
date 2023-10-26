%Matrix
A =[1 2 3 ; 2 1 1 ; 3 2 1]
B =[4 4 5 ; 6 1 2 ; 3 5 5]

%Determinan
aA=det(A)
aB=det(B)

%Ukuran Dari Matrix
aA=size(A)
aB=size(B)

%Trace
aA=trace(A)
aB=trace(B)

%Norm
aA=norm(A)
aB=norm(B)

%c
eC=A+B
fC=A-B
gC=A*B
hC=A.*B
iC=A^2
jC=A.^2

%Transpose Matrik A ke B
aA=A'
bB=B'

%c
lC=A./B
mC=A.\B
nC=A/B

%Invert
aA=inv(A)
aB=inv(B)

%c
pC=null(A)
qC=orth(A)
rc=rref(A)

%Eigen
aA=eig(A)
aB=eig(B)

%Singular
aA=svd(A)
aB=svd(B)

%Segitiga Atas
aA=triu(A)
aB=triu(B)

%Segitiga Bawah
aA=tril(A)
aB=tril(B)

%Nilai Maksimum
aA=max(max(A))
aB=max(max(B))

%Nilai Minimum
aA=min(min(A))
aB=min(min(B))

%Jumlah Kolom Elemen
aA=sum(A,1)
aA=sum(A,2)
aB=sum(B,1)
aB=sum(B,2)

%Diagonal
aA=diag(A)
aB=diag(B)

%Matrik 5x5
Z=eye(5)

%Matrik 3x3 Dengan Elemen Nol
Y=zeros(3,3)

%Matrik 4x4 Elemen 1
X=ones(4,4)

%Matrik 3x4 Elemen Terdistribusi Antara 0 Dan 1
W=rand(3,4)

%Matrik 3x4 Elemen Terdistribusi Normal
V=randn(3,4)