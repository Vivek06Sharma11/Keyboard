# Keyboard
# -*- coding: utf-8 -*-

# Form implementation generated from reading ui file 'Keyboard2.ui'
#
# Created by: PyQt5 UI code generator 5.11.3
#
# WARNING! All changes made in this file will be lost!



#python -m PyQt5.uic.pyuic -x [FILENAME].ui -o [FILENAME].py

from PyQt5 import QtCore, QtGui, QtWidgets
import os
global texts
texts=""
class Ui_MainWindow(object):
    def setupUi(self, MainWindow):
        self.flag='0'
        MainWindow.setObjectName("MainWindow")
        MainWindow.resize(2350, 349)
        self.centralwidget = QtWidgets.QWidget(MainWindow)
        self.centralwidget.setObjectName("centralwidget")
        self.gridLayout_2 = QtWidgets.QGridLayout(self.centralwidget)
        self.gridLayout_2.setObjectName("gridLayout_2")
        self.gridLayout = QtWidgets.QGridLayout()
        self.gridLayout.setObjectName("gridLayout")
        self.gridLayout_2.addLayout(self.gridLayout, 0, 0, 1, 1)
        self.text = QtWidgets.QLineEdit(self.centralwidget)
        self.text.setObjectName("text")
        self.text.setText(texts)
        self.gridLayout_2.addWidget(self.text, 1, 1, 1, 32)
        self.f1 = QtWidgets.QPushButton(self.centralwidget)
        self.f1.setObjectName("f1")
        self.gridLayout_2.addWidget(self.f1, 2, 1, 1, 1)
        self.f2 = QtWidgets.QPushButton(self.centralwidget)
        self.f2.setObjectName("f2")
        self.gridLayout_2.addWidget(self.f2, 2, 2, 1, 2)
        self.f3 = QtWidgets.QPushButton(self.centralwidget)
        self.f3.setObjectName("f3")
        self.gridLayout_2.addWidget(self.f3, 2, 4, 1, 2)
        self.f4 = QtWidgets.QPushButton(self.centralwidget)
        self.f4.setObjectName("f4")
        self.f4.clicked.connect(self.button_f4)
        self.gridLayout_2.addWidget(self.f4, 2, 6, 1, 2)
        self.f5 = QtWidgets.QPushButton(self.centralwidget)
        self.f5.setObjectName("f5")
        self.gridLayout_2.addWidget(self.f5, 2, 8, 1, 2)
        self.f6 = QtWidgets.QPushButton(self.centralwidget)
        self.f6.setObjectName("f6")
        self.gridLayout_2.addWidget(self.f6, 2, 10, 1, 2)
        self.f7 = QtWidgets.QPushButton(self.centralwidget)
        self.f7.setObjectName("f7")
        self.gridLayout_2.addWidget(self.f7, 2, 12, 1, 2)
        self.f8 = QtWidgets.QPushButton(self.centralwidget)
        self.f8.setObjectName("f8")
        self.gridLayout_2.addWidget(self.f8, 2, 14, 1, 2)
        self.f9 = QtWidgets.QPushButton(self.centralwidget)
        self.f9.setObjectName("f9")
        self.gridLayout_2.addWidget(self.f9, 2, 16, 1, 2)
        self.f10 = QtWidgets.QPushButton(self.centralwidget)
        self.f10.setObjectName("f10")
        self.gridLayout_2.addWidget(self.f10, 2, 18, 1, 2)
        self.f11 = QtWidgets.QPushButton(self.centralwidget)
        self.f11.setObjectName("f11")
        self.gridLayout_2.addWidget(self.f11, 2, 20, 1, 2)
        self.f12 = QtWidgets.QPushButton(self.centralwidget)
        self.f12.setObjectName("f12")
        self.gridLayout_2.addWidget(self.f12, 2, 22, 1, 3)
        self.print = QtWidgets.QPushButton(self.centralwidget)
        self.print.setObjectName("print")
        self.gridLayout_2.addWidget(self.print, 2, 25, 1, 2)
        self.insert = QtWidgets.QPushButton(self.centralwidget)
        self.insert.setObjectName("insert")
        self.gridLayout_2.addWidget(self.insert, 2, 27, 1, 2)
        self.Delete = QtWidgets.QPushButton(self.centralwidget)
        self.Delete.setObjectName("Delete")
        self.gridLayout_2.addWidget(self.Delete, 2, 29, 1, 1)
        self.multiple = QtWidgets.QPushButton(self.centralwidget)
        self.multiple.setObjectName("multiple")
        self.multiple.clicked.connect(self.button_multiple)
        self.gridLayout_2.addWidget(self.multiple, 2, 30, 1, 1)
        self.divide = QtWidgets.QPushButton(self.centralwidget)
        self.divide.setObjectName("divide")
        self.divide.clicked.connect(self.button_divide)
        self.gridLayout_2.addWidget(self.divide, 2, 31, 1, 1)
        self.pushButton_82 = QtWidgets.QPushButton(self.centralwidget)
        self.pushButton_82.setObjectName("pushButton_82")
        self.gridLayout_2.addWidget(self.pushButton_82, 2, 32, 1, 1)
        self.pushButton_75 = QtWidgets.QPushButton(self.centralwidget)
        self.pushButton_75.setObjectName("pushButton_75")
        self.gridLayout_2.addWidget(self.pushButton_75, 3, 1, 1, 1)
        self.n1 = QtWidgets.QPushButton(self.centralwidget)
        self.n1.setObjectName("n1")
        self.n1.clicked.connect(self.button_n1)
        self.gridLayout_2.addWidget(self.n1, 3, 2, 1, 2)
        self.n2 = QtWidgets.QPushButton(self.centralwidget)
        self.n2.setObjectName("n2")
        self.n2.clicked.connect(self.button_n2)
        self.gridLayout_2.addWidget(self.n2, 3, 4, 1, 2)
        self.n3 = QtWidgets.QPushButton(self.centralwidget)
        self.n3.setObjectName("n3")
        self.n3.clicked.connect(self.button_n3)
        self.gridLayout_2.addWidget(self.n3, 3, 6, 1, 2)
        self.n4 = QtWidgets.QPushButton(self.centralwidget)
        self.n4.setObjectName("n4")
        self.n4.clicked.connect(self.button_n4)
        self.gridLayout_2.addWidget(self.n4, 3, 8, 1, 2)
        self.n5 = QtWidgets.QPushButton(self.centralwidget)
        self.n5.setObjectName("n5")
        self.n5.clicked.connect(self.button_n5)
        self.gridLayout_2.addWidget(self.n5, 3, 10, 1, 2)
        self.n6 = QtWidgets.QPushButton(self.centralwidget)
        self.n6.setObjectName("n6")
        self.n6.clicked.connect(self.button_n6)
        self.gridLayout_2.addWidget(self.n6, 3, 12, 1, 2)
        self.n7 = QtWidgets.QPushButton(self.centralwidget)
        self.n7.setObjectName("n7")
        self.n7.clicked.connect(self.button_n7)
        self.gridLayout_2.addWidget(self.n7, 3, 14, 1, 2)
        self.n8 = QtWidgets.QPushButton(self.centralwidget)
        self.n8.setObjectName("n8")
        self.n8.clicked.connect(self.button_n8)
        self.gridLayout_2.addWidget(self.n8, 3, 16, 1, 2)
        self.n9 = QtWidgets.QPushButton(self.centralwidget)
        self.n9.setObjectName("n9")
        self.n9.clicked.connect(self.button_n9)
        self.gridLayout_2.addWidget(self.n9, 3, 18, 1, 2)
        self.n0 = QtWidgets.QPushButton(self.centralwidget)
        self.n0.setObjectName("n0")
        self.n0.clicked.connect(self.button_n0)
        self.gridLayout_2.addWidget(self.n0, 3, 20, 1, 2)
        self.US = QtWidgets.QPushButton(self.centralwidget)
        self.US.setObjectName("US")
        self.US.clicked.connect(self.button_US)
        self.gridLayout_2.addWidget(self.US, 3, 22, 1, 3)
        self.Equal = QtWidgets.QPushButton(self.centralwidget)
        self.Equal.setObjectName("Equal")
        self.Equal.clicked.connect(self.button_Equal)
        self.gridLayout_2.addWidget(self.Equal, 3, 25, 1, 2)
        self.Backspace = QtWidgets.QPushButton(self.centralwidget)
        self.Backspace.setObjectName("Backspace")
        self.Backspace.clicked.connect(self.button_Backspace)
        self.gridLayout_2.addWidget(self.Backspace, 3, 27, 1, 3)
        self.add = QtWidgets.QPushButton(self.centralwidget)
        self.add.setObjectName("add")
        self.add.clicked.connect(self.button_add)
        self.gridLayout_2.addWidget(self.add, 3, 30, 1, 1)
        self.sub = QtWidgets.QPushButton(self.centralwidget)
        self.sub.setObjectName("sub")
        self.sub.clicked.connect(self.button_sub)
        self.gridLayout_2.addWidget(self.sub, 3, 31, 1, 1)
        self.num_ik = QtWidgets.QPushButton(self.centralwidget)
        self.num_ik.setObjectName("num_ik")
        self.gridLayout_2.addWidget(self.num_ik, 3, 32, 1, 1)
        self.TAB = QtWidgets.QPushButton(self.centralwidget)
        self.TAB.setObjectName("TAB")
        self.TAB.clicked.connect(self.button_TAB)
        self.gridLayout_2.addWidget(self.TAB, 4, 1, 1, 2)
        self.Q = QtWidgets.QPushButton(self.centralwidget)
        self.Q.setObjectName("Q")
        self.Q.clicked.connect(self.button_q)
        self.gridLayout_2.addWidget(self.Q, 4, 3, 1, 2)
        self.W = QtWidgets.QPushButton(self.centralwidget)
        self.W.setObjectName("W")
        self.W.clicked.connect(self.button_w)
        self.gridLayout_2.addWidget(self.W, 4, 5, 1, 2)
        self.E = QtWidgets.QPushButton(self.centralwidget)
        self.E.setObjectName("E")
        self.E.clicked.connect(self.button_e)
        self.gridLayout_2.addWidget(self.E, 4, 7, 1, 2)
        self.R = QtWidgets.QPushButton(self.centralwidget)
        self.R.setObjectName("R")
        self.R.clicked.connect(self.button_r)
        self.gridLayout_2.addWidget(self.R, 4, 9, 1, 2)
        self.T = QtWidgets.QPushButton(self.centralwidget)
        self.T.setObjectName("T")
        self.T.clicked.connect(self.button_t)
        self.gridLayout_2.addWidget(self.T, 4, 11, 1, 2)
        self.Y = QtWidgets.QPushButton(self.centralwidget)
        self.Y.setObjectName("Y")
        self.Y.clicked.connect(self.button_y)
        self.gridLayout_2.addWidget(self.Y, 4, 13, 1, 2)
        self.U = QtWidgets.QPushButton(self.centralwidget)
        self.U.setObjectName("U")
        self.U.clicked.connect(self.button_u)
        self.gridLayout_2.addWidget(self.U, 4, 15, 1, 2)
        self.I = QtWidgets.QPushButton(self.centralwidget)
        self.I.setObjectName("I")
        self.I.clicked.connect(self.button_i)
        self.gridLayout_2.addWidget(self.I, 4, 17, 1, 2)
        self.O = QtWidgets.QPushButton(self.centralwidget)
        self.O.setObjectName("O")
        self.O.clicked.connect(self.button_o)
        self.gridLayout_2.addWidget(self.O, 4, 19, 1, 2)
        self.P = QtWidgets.QPushButton(self.centralwidget)
        self.P.setObjectName("P")
        self.P.clicked.connect(self.button_p)
        self.gridLayout_2.addWidget(self.P, 4, 21, 1, 2)
        self.SBO = QtWidgets.QPushButton(self.centralwidget)
        self.SBO.setObjectName("SBO")
        self.gridLayout_2.addWidget(self.SBO, 4, 24, 1, 2)
        self.SBC = QtWidgets.QPushButton(self.centralwidget)
        self.SBC.setObjectName("SBC")
        self.gridLayout_2.addWidget(self.SBC, 4, 26, 1, 2)
        self.B_slash = QtWidgets.QPushButton(self.centralwidget)
        self.B_slash.setObjectName("B_slash")
        self.gridLayout_2.addWidget(self.B_slash, 4, 28, 1, 2)
        self.seven = QtWidgets.QPushButton(self.centralwidget)
        self.seven.setObjectName("seven")
        self.seven.clicked.connect(self.button_seven)
        self.gridLayout_2.addWidget(self.seven, 4, 30, 1, 1)
        self.eight = QtWidgets.QPushButton(self.centralwidget)
        self.eight.setObjectName("eight")
        self.eight.clicked.connect(self.button_eight)
        self.gridLayout_2.addWidget(self.eight, 4, 31, 1, 1)
        self.nine = QtWidgets.QPushButton(self.centralwidget)
        self.nine.setObjectName("nine")
        self.nine.clicked.connect(self.button_nine)
        self.gridLayout_2.addWidget(self.nine, 4, 32, 1, 1)
        self.Capslock = QtWidgets.QPushButton(self.centralwidget)
        self.Capslock.setObjectName("Capslock")
        self.Capslock.clicked.connect(self.caps)
        self.gridLayout_2.addWidget(self.Capslock, 5, 1, 1, 3)
        self.A = QtWidgets.QPushButton(self.centralwidget)
        self.A.setContextMenuPolicy(QtCore.Qt.DefaultContextMenu)
        self.A.setObjectName("A")
        self.A.clicked.connect(self.button_a)
        self.gridLayout_2.addWidget(self.A, 5, 4, 1, 2)
        self.S = QtWidgets.QPushButton(self.centralwidget)
        self.S.setObjectName("S")
        self.S.clicked.connect(self.button_s)
        self.gridLayout_2.addWidget(self.S, 5, 6, 1, 2)
        self.D = QtWidgets.QPushButton(self.centralwidget)
        self.D.setObjectName("D")
        self.D.clicked.connect(self.button_d)
        self.gridLayout_2.addWidget(self.D, 5, 8, 1, 2)
        self.F = QtWidgets.QPushButton(self.centralwidget)
        self.F.setObjectName("F")
        self.F.clicked.connect(self.button_f)
        self.gridLayout_2.addWidget(self.F, 5, 10, 1, 2)
        self.G = QtWidgets.QPushButton(self.centralwidget)
        self.G.setObjectName("G")
        self.G.clicked.connect(self.button_g)
        self.gridLayout_2.addWidget(self.G, 5, 12, 1, 2)
        self.H = QtWidgets.QPushButton(self.centralwidget)
        self.H.setObjectName("H")
        self.H.clicked.connect(self.button_h)
        self.gridLayout_2.addWidget(self.H, 5, 14, 1, 2)
        self.J = QtWidgets.QPushButton(self.centralwidget)
        self.J.setObjectName("J")
        self.J.clicked.connect(self.button_j)
        self.gridLayout_2.addWidget(self.J, 5, 16, 1, 2)
        self.K = QtWidgets.QPushButton(self.centralwidget)
        self.K.setObjectName("K")
        self.K.clicked.connect(self.button_k)
        self.gridLayout_2.addWidget(self.K, 5, 18, 1, 2)
        self.L = QtWidgets.QPushButton(self.centralwidget)
        self.L.setObjectName("L")
        self.L.clicked.connect(self.button_l)
        self.gridLayout_2.addWidget(self.L, 5, 20, 1, 2)
        self.S_collen = QtWidgets.QPushButton(self.centralwidget)
        self.S_collen.setObjectName("S_collen")
        self.S_collen.clicked.connect(self.button_S_collen)
        self.gridLayout_2.addWidget(self.S_collen, 5, 22, 1, 3)
        self.S_Cots = QtWidgets.QPushButton(self.centralwidget)
        self.S_Cots.setObjectName("S_Cots")
        self.S_Cots.clicked.connect(self.button_S_Cots)
        self.gridLayout_2.addWidget(self.S_Cots, 5, 25, 1, 2)
        self.Enter = QtWidgets.QPushButton(self.centralwidget)
        self.Enter.setObjectName("Enter")
        self.Enter.clicked.connect(self.button_Enter)
        self.gridLayout_2.addWidget(self.Enter, 5, 27, 1, 3)
        self.four = QtWidgets.QPushButton(self.centralwidget)
        self.four.setObjectName("four")
        self.four.clicked.connect(self.button_four)
        self.gridLayout_2.addWidget(self.four, 5, 30, 1, 1)
        self.five = QtWidgets.QPushButton(self.centralwidget)
        self.five.setObjectName("five")
        self.five.clicked.connect(self.button_five)
        self.gridLayout_2.addWidget(self.five, 5, 31, 1, 1)
        self.six = QtWidgets.QPushButton(self.centralwidget)
        self.six.setObjectName("six")
        self.six.clicked.connect(self.button_six)
        self.gridLayout_2.addWidget(self.six, 5, 32, 1, 1)
        self.Shift = QtWidgets.QPushButton(self.centralwidget)
        self.Shift.setObjectName("Shift")
        self.Shift.clicked.connect(self.button_shift)
        self.gridLayout_2.addWidget(self.Shift, 6, 1, 1, 4)
        self.Z = QtWidgets.QPushButton(self.centralwidget)
        self.Z.setObjectName("Z")
        self.Z.clicked.connect(self.button_z)
        self.gridLayout_2.addWidget(self.Z, 6, 5, 1, 2)
        self.X = QtWidgets.QPushButton(self.centralwidget)
        self.X.setObjectName("X")
        self.X.clicked.connect(self.button_x)
        self.gridLayout_2.addWidget(self.X, 6, 7, 1, 2)
        self.C = QtWidgets.QPushButton(self.centralwidget)
        self.C.setObjectName("C")
        self.C.clicked.connect(self.button_c)
        self.gridLayout_2.addWidget(self.C, 6, 9, 1, 2)
        self.V = QtWidgets.QPushButton(self.centralwidget)
        self.V.setObjectName("V")
        self.V.clicked.connect(self.button_v)
        self.gridLayout_2.addWidget(self.V, 6, 11, 1, 2)
        self.B = QtWidgets.QPushButton(self.centralwidget)
        self.B.setObjectName("B")
        self.B.clicked.connect(self.button_b)
        self.gridLayout_2.addWidget(self.B, 6, 13, 1, 2)
        self.N = QtWidgets.QPushButton(self.centralwidget)
        self.N.setObjectName("N")
        self.N.clicked.connect(self.button_n)
        self.gridLayout_2.addWidget(self.N, 6, 15, 1, 2)
        self.M = QtWidgets.QPushButton(self.centralwidget)
        self.M.setObjectName("M")
        self.M.clicked.connect(self.button_m)
        self.gridLayout_2.addWidget(self.M, 6, 17, 1, 2)
        self.Coma = QtWidgets.QPushButton(self.centralwidget)
        self.Coma.setObjectName("Coma")
        self.Coma.clicked.connect(self.button_Coma)
        self.gridLayout_2.addWidget(self.Coma, 6, 19, 1, 2)
        self.F_STOP = QtWidgets.QPushButton(self.centralwidget)
        self.F_STOP.setObjectName("F_STOP")
        self.F_STOP.clicked.connect(self.button_F_STOP)
        self.gridLayout_2.addWidget(self.F_STOP, 6, 21, 1, 2)
        self.Divission = QtWidgets.QPushButton(self.centralwidget)
        self.Divission.setObjectName("Divission")
        self.Divission.clicked.connect(self.button_Divission)
        self.gridLayout_2.addWidget(self.Divission, 6, 23, 1, 3)
        self.shift = QtWidgets.QPushButton(self.centralwidget)
        self.shift.setObjectName("shift")
        self.shift.clicked.connect(self.button_shift)
        self.gridLayout_2.addWidget(self.shift, 6, 26, 1, 4)
        self.one = QtWidgets.QPushButton(self.centralwidget)
        self.one.setObjectName("one")
        self.one.clicked.connect(self.button_one)
        self.gridLayout_2.addWidget(self.one, 6, 30, 1, 1)
        self.two = QtWidgets.QPushButton(self.centralwidget)
        self.two.setObjectName("two")
        self.two.clicked.connect(self.button_two)
        self.gridLayout_2.addWidget(self.two, 6, 31, 1, 1)
        self.three = QtWidgets.QPushButton(self.centralwidget)
        self.three.setObjectName("three")
        self.three.clicked.connect(self.button_three)
        self.gridLayout_2.addWidget(self.three, 6, 32, 1, 1)
        self.Ctrl = QtWidgets.QPushButton(self.centralwidget)
        self.Ctrl.setObjectName("Ctrl")
        self.gridLayout_2.addWidget(self.Ctrl, 7, 1, 2, 2)
        self.fn = QtWidgets.QPushButton(self.centralwidget)
        self.fn.setObjectName("fn")
        self.gridLayout_2.addWidget(self.fn, 7, 3, 2, 2)
        self.win = QtWidgets.QPushButton(self.centralwidget)
        self.win.setObjectName("win")
        self.gridLayout_2.addWidget(self.win, 7, 5, 2, 2)
        self.Alt = QtWidgets.QPushButton(self.centralwidget)
        self.Alt.setObjectName("Alt")
        self.Alt.clicked.connect(self.button_alt)
        self.gridLayout_2.addWidget(self.Alt, 7, 7, 2, 2)
        self.Space = QtWidgets.QPushButton(self.centralwidget)
        self.Space.setObjectName("Space")
        self.Space.clicked.connect(self.button_Space)
        self.gridLayout_2.addWidget(self.Space, 7, 9, 2, 10)
        self.alt = QtWidgets.QPushButton(self.centralwidget)
        self.alt.setObjectName("alt")
        self.alt.clicked.connect(self.button_alt)
        self.gridLayout_2.addWidget(self.alt, 7, 19, 2, 2)
        self.ctrl = QtWidgets.QPushButton(self.centralwidget)
        self.ctrl.setObjectName("ctrl")
        self.gridLayout_2.addWidget(self.ctrl, 7, 21, 2, 3)
        self.up = QtWidgets.QPushButton(self.centralwidget)
        self.up.setObjectName("up")
        self.up.clicked.connect(self.button_up)
        self.gridLayout_2.addWidget(self.up, 7, 27, 1, 2)
        self.zero = QtWidgets.QPushButton(self.centralwidget)
        self.zero.setObjectName("zero")
        self.zero.clicked.connect(self.button_zero)
        self.gridLayout_2.addWidget(self.zero, 7, 30, 2, 1)
        self.dot = QtWidgets.QPushButton(self.centralwidget)
        self.dot.setObjectName("dot")
        self.dot.clicked.connect(self.button_dot)
        self.gridLayout_2.addWidget(self.dot, 7, 31, 2, 1)
        self.enter = QtWidgets.QPushButton(self.centralwidget)
        self.enter.setObjectName("enter")
        self.enter.clicked.connect(self.button_enter)
        self.gridLayout_2.addWidget(self.enter, 7, 32, 2, 1)
        self.left = QtWidgets.QPushButton(self.centralwidget)
        self.left.setObjectName("left")
        self.left.clicked.connect(self.button_left)
        self.gridLayout_2.addWidget(self.left, 8, 25, 1, 2)
        self.down = QtWidgets.QPushButton(self.centralwidget)
        self.down.setObjectName("down")
        self.down.clicked.connect(self.button_down)
        self.gridLayout_2.addWidget(self.down, 8, 27, 1, 2)
        self.right = QtWidgets.QPushButton(self.centralwidget)
        self.right.setObjectName("right")
        self.right.clicked.connect(self.button_right)
        self.gridLayout_2.addWidget(self.right, 8, 29, 1, 1)
        MainWindow.setCentralWidget(self.centralwidget)
        self.menubar = QtWidgets.QMenuBar(MainWindow)
        self.menubar.setGeometry(QtCore.QRect(0, 0, 2350, 26))
        self.menubar.setObjectName("menubar")
        MainWindow.setMenuBar(self.menubar)
        self.statusbar = QtWidgets.QStatusBar(MainWindow)
        self.statusbar.setObjectName("statusbar")
        MainWindow.setStatusBar(self.statusbar)

        self.retranslateUi(MainWindow)
        QtCore.QMetaObject.connectSlotsByName(MainWindow)

    def retranslateUi(self, MainWindow):
        _translate = QtCore.QCoreApplication.translate
        MainWindow.setWindowTitle(_translate("MainWindow", "MainWindow"))
        self.f1.setText(_translate("MainWindow", "f1"))
        self.f2.setText(_translate("MainWindow", "f2"))
        self.f3.setText(_translate("MainWindow", "f3"))
        self.f4.setText(_translate("MainWindow", "f4"))
        self.f5.setText(_translate("MainWindow", "f5"))
        self.f6.setText(_translate("MainWindow", "f6"))
        self.f7.setText(_translate("MainWindow", "f7"))
        self.f8.setText(_translate("MainWindow", "f8"))
        self.f9.setText(_translate("MainWindow", "f9"))
        self.f10.setText(_translate("MainWindow", "f10"))
        self.f11.setText(_translate("MainWindow", "f11"))
        self.f12.setText(_translate("MainWindow", "f12"))
        self.print.setText(_translate("MainWindow", "print"))
        self.insert.setText(_translate("MainWindow", "insert"))
        self.Delete.setText(_translate("MainWindow", "Delete"))
        self.multiple.setText(_translate("MainWindow", "*"))
        self.divide.setText(_translate("MainWindow", "/"))
        self.pushButton_82.setText(_translate("MainWindow", "OFF"))
        self.pushButton_75.setText(_translate("MainWindow", "~ `"))
        self.n1.setText(_translate("MainWindow", "1 !"))
        self.n2.setText(_translate("MainWindow", "2 @"))
        self.n3.setText(_translate("MainWindow", "3 #"))
        self.n4.setText(_translate("MainWindow", "4 $"))
        self.n5.setText(_translate("MainWindow", "5 %"))
        self.n6.setText(_translate("MainWindow", "6 ^"))
        self.n7.setText(_translate("MainWindow", "7 &"))
        self.n8.setText(_translate("MainWindow", "8 *"))
        self.n9.setText(_translate("MainWindow", "9 ("))
        self.n0.setText(_translate("MainWindow", "0 )"))
        self.US.setText(_translate("MainWindow", "- _"))
        self.Equal.setText(_translate("MainWindow", " = +"))
        self.Backspace.setText(_translate("MainWindow", "Backspace"))
        self.add.setText(_translate("MainWindow", "+"))
        self.sub.setText(_translate("MainWindow", "-"))
        self.num_ik.setText(_translate("MainWindow", "num ik"))
        self.TAB.setText(_translate("MainWindow", "Tab"))
        self.Q.setText(_translate("MainWindow", "Q"))
        self.W.setText(_translate("MainWindow", "W"))
        self.E.setText(_translate("MainWindow", "E"))
        self.R.setText(_translate("MainWindow", "R"))
        self.T.setText(_translate("MainWindow", "T"))
        self.Y.setText(_translate("MainWindow", "Y"))
        self.U.setText(_translate("MainWindow", "U"))
        self.I.setText(_translate("MainWindow", "I"))
        self.O.setText(_translate("MainWindow", "O"))
        self.P.setText(_translate("MainWindow", "P"))
        self.SBO.setText(_translate("MainWindow", "[ {"))
        self.SBC.setText(_translate("MainWindow", "} ]"))
        self.B_slash.setText(_translate("MainWindow", "| \\"))
        self.seven.setText(_translate("MainWindow", "7"))
        self.eight.setText(_translate("MainWindow", "8"))
        self.nine.setText(_translate("MainWindow", "9"))
        self.Capslock.setText(_translate("MainWindow", "Caps lock"))
        self.A.setText(_translate("MainWindow", "A"))
        self.S.setText(_translate("MainWindow", "S"))
        self.D.setText(_translate("MainWindow", "D"))
        self.F.setText(_translate("MainWindow", "F"))
        self.G.setText(_translate("MainWindow", "G"))
        self.H.setText(_translate("MainWindow", "H"))
        self.J.setText(_translate("MainWindow", "J"))
        self.K.setText(_translate("MainWindow", "K"))
        self.L.setText(_translate("MainWindow", "L"))
        self.S_collen.setText(_translate("MainWindow", ": ;"))
        self.S_Cots.setText(_translate("MainWindow", "\" \'"))
        self.Enter.setText(_translate("MainWindow", "Enter"))
        self.four.setText(_translate("MainWindow", "4"))
        self.five.setText(_translate("MainWindow", "5"))
        self.six.setText(_translate("MainWindow", "6"))
        self.Shift.setText(_translate("MainWindow", "Shift"))
        self.Z.setText(_translate("MainWindow", "Z"))
        self.X.setText(_translate("MainWindow", "X"))
        self.C.setText(_translate("MainWindow", "C"))
        self.V.setText(_translate("MainWindow", "V"))
        self.B.setText(_translate("MainWindow", "B"))
        self.N.setText(_translate("MainWindow", "N"))
        self.M.setText(_translate("MainWindow", "M"))
        self.Coma.setText(_translate("MainWindow", "< ,"))
        self.F_STOP.setText(_translate("MainWindow", "> ."))
        self.Divission.setText(_translate("MainWindow", "? /"))
        self.shift.setText(_translate("MainWindow", "Shift"))
        self.one.setText(_translate("MainWindow", "1"))
        self.two.setText(_translate("MainWindow", "2"))
        self.three.setText(_translate("MainWindow", "3"))
        self.Ctrl.setText(_translate("MainWindow", "ctrl"))
        self.fn.setText(_translate("MainWindow", "fn"))
        self.win.setText(_translate("MainWindow", "win"))
        self.Alt.setText(_translate("MainWindow", "alt"))
        self.Space.setText(_translate("MainWindow", "space"))
        self.alt.setText(_translate("MainWindow", "alt"))
        self.ctrl.setText(_translate("MainWindow", "ctrl"))
        self.up.setText(_translate("MainWindow", "up"))
        self.zero.setText(_translate("MainWindow", "0"))
        self.dot.setText(_translate("MainWindow", "."))
        self.enter.setText(_translate("MainWindow", "enter"))
        self.left.setText(_translate("MainWindow", "left"))
        self.down.setText(_translate("MainWindow", "down"))
        self.right.setText(_translate("MainWindow", "right"))


    
    

    def caps(self):
        if self.flag=='0':
            self.flag='1';
        elif self.flag=='1':
            self.flag='0';
    def button_q(self):
        global texts
        if self.flag=='0':
            texts+='q'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='Q'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='Q'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='q'
            self.text.setText(texts)
            self.flag='1';
            
            
    def button_w(self):
        global texts
        if self.flag=='0':
            texts+='w'
            self.text.setText(texts);
        elif self.flag=='1':
            texts+='W'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='W'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='w'
            self.text.setText(texts)
            self.flag='1';
    def button_e(self):
        global texts
        if self.flag=='0':
            texts+='e'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='E'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='E'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='e'
            self.text.setText(texts)
            self.flag='1';
    def button_r(self):
        global texts
        if self.flag=='0':
            texts+='r'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='R'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='R'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='r'
            self.text.setText(texts)
            self.flag='1';
    def button_t(self):
        global texts
        if self.flag=='0':
            texts+='t'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='T'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='T'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='t'
            self.text.setText(texts)
            self.flag='1';
    def button_y(self):
        global texts
        if self.flag=='0':
            texts+='y'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='Y'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='Y'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='y'
            self.text.setText(texts)
            self.flag='1';
    def button_u(self):
        global texts
        if self.flag=='0':
            texts+='u'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='U'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='U'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='u'
            self.text.setText(texts)
            self.flag='1';
    def button_i(self):
        global texts
        if self.flag=='0':
            texts+='i'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='I'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='I'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='i'
            self.text.setText(texts)
            self.flag='1';
    def button_o(self):
        global texts
        if self.flag=='0':
            texts+='o'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='O'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='O'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='o'
            self.text.setText(texts)
            self.flag='1';
    def button_p(self):
        global texts
        if self.flag=='0':
            texts+='p'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='P'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='P'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='p'
            self.text.setText(texts)
            self.flag='1';


    def button_a(self):
        global texts
        if self.flag=='0':
            texts+='a'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='A'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='A'
            self.text.setText(texts)
            self.flag='0'
        elif self.flag=='3':
            texts+='a'
            self.text.setText(texts)
            self.flag='1';
    def button_s(self):
        global texts
        if self.flag=='0':
            texts+='s'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='S'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='S'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='s'
            self.text.setText(texts)
            self.flag='1';
    def button_d(self):
        global texts
        if self.flag=='0':
            texts+='d'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='D'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='D'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='d'
            self.text.setText(texts)
            self.flag='1';
    def button_f(self):
        global texts
        if self.flag=='0':
            texts+='f'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='F'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='F'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='f'
            self.text.setText(texts)
            self.flag='1';
    def button_g(self):
        global texts
        if self.flag=='0':
            texts+='g'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='G'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='G'
            self.text.setText(texts)
        elif self.flag=='3':
            texts+='g'
            self.text.setText(texts)
            self.flag='1';
    def button_h(self):
        global texts
        if self.flag=='0':
            texts+='h'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='H'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='H'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='h'
            self.text.setText(texts)
            self.flag='1';
    def button_j(self):
        global texts
        if self.flag=='0':
            texts+='j'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='J'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='J'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='j'
            self.text.setText(texts)
            self.flag='1';
    def button_k(self):
        global texts
        if self.flag=='0':
            texts+='k'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='K'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='K'
            self.text.setText(texts)
        elif self.flag=='3':
            texts+='k'
            self.text.setText(texts)
            self.flag='1';
    def button_l(self):
        global texts
        if self.flag=='0':
            texts+='l'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='L'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='L'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='l'
            self.text.setText(texts)
            self.flag='1';


    def button_z(self):
        global texts
        if self.flag=='0':
            texts+='z'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='Z'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='Z'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='z'
            self.text.setText(texts)
            self.flag='1';
    def button_x(self):
        global texts
        if self.flag=='0':
            texts+='x'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='X'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='X'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='x'
            self.text.setText(texts)
            self.flag='1';
    def button_c(self):
        global texts
        if self.flag=='0':
            texts+='c'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='C'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='C'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='C'
            self.text.setText(texts)
            self.flag='1';
    def button_v(self):
        global texts
        if self.flag=='0':
            texts+='v'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='V'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='V'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='v'
            self.text.setText(texts)
            self.flag='1';
    def button_b(self):
        global texts
        if self.flag=='0':
            texts+='b'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='B'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='B'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='b'
            self.text.setText(texts)
            self.flag='1';
    def button_n(self):
        global texts
        if self.flag=='0':
            texts+='n'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='N'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='N'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='n'
            self.text.setText(texts)
            self.flag='1';
    def button_m(self):
        global texts
        if self.flag=='0':
            texts+='m'
            self.text.setText(texts)
        elif self.flag=='1':
            texts+='M'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='M'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='m'
            self.text.setText(texts)
            self.flag='1';

        

    def button_n1(self):
        global texts
        if self.flag=='2':
            texts+='!'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='!'
            self.text.setText(texts)
            self.flag='1';
        elif self.flag=='0' or self.flag=='1':
            texts+='1'
            self.text.setText(texts)
    def button_n2(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='2'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='@'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='@'
            self.text.setText(texts)
            self.flag='1';
    def button_n3(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='3'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='#'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='#'
            self.text.setText(texts)
            self.flag='1';
    def button_n4(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='4'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='$'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='$'
            self.text.setText(texts)
            self.flag='1';
    def button_n5(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='5'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='%'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='%'
            self.text.setText(texts)
            self.flag='1';
    def button_n6(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='6'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='^'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='^'
            self.text.setText(texts)
            self.flag='1';
    def button_n7(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='7'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='&'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='&'
            self.text.setText(texts)
            self.flag='1';
    def button_n8(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='8'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='*'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='*'
            self.text.setText(texts)
            self.flag='1';
    def button_n9(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='9'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='('
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='('
            self.text.setText(texts)
            self.flag='1';
    def button_n0(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='0'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+=')'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+=')'
            self.text.setText(texts)
            self.flag='1';
        

    def button_S_collen(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+=';'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+=':'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+=':'
            self.text.setText(texts)
            self.flag='1';
    def button_S_Cots(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+="'"
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='"'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='"'
            self.text.setText(texts)
            self.flag='1';
    def button_Enter(self):
        global texts
        texts+=' '
        self.text.setText(texts)
    def button_US(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='-'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='_'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='_'
            self.text.setText(texts)
            self.flag='1';
    def button_Equal(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='='
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='+'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='+'
            self.text.setText(texts)
            self.flag='1';
    def button_add(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='+'
            self.text.setText(texts)
    def button_Backspace(self):
        global texts
        self.text.backspace()
        texts=self.text.text()
    def button_sub(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='-'
            self.text.setText(texts)
    def button_TAB(self):
        global texts
        texts+='    '
        self.text.setText(texts)
    def button_multiple(self):
        global texts
        texts+='*'
        self.text.setText(texts)
    def button_divide(self):
        texts+='/'
        self.text.setText(texts)
    def button_Divission(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='/'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='?'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='?'
            self.text.setText(texts)
            self.flag='1';
    def button_Coma(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+=','
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='<'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='<'
            self.text.setText(texts)
            self.flag='1';
    def button_F_STOP(self):
        global texts
        if self.flag=='0' or self.flag=='1':
            texts+='.'
            self.text.setText(texts)
        elif self.flag=='2':
            texts+='>'
            self.text.setText(texts)
            self.flag='0';
        elif self.flag=='3':
            texts+='>'
            self.text.setText(texts)
            self.flag='1';
    def button_Space(self):
        global texts
        texts+=' '
        self.text.setText(texts)


    def button_one(self):
        global texts
        texts+='1'
        self.text.setText(texts)
    def button_two(self):
        global texts
        texts+='2'
        self.text.setText(texts)
    def button_three(self):
        global texts
        texts+='3'
        self.text.setText(texts)
    def button_four(self):
        global texts
        texts+='4'
        self.text.setText(texts)
    def button_five(self):
        global texts
        texts+='5'
        self.text.setText(texts)
    def button_six(self):
        global texts
        texts+='6'
        self.text.setText(texts)
    def button_seven(self):
        global texts
        texts+='7'
        self.text.setText(texts)
    def button_eight(self):
        global texts
        texts+='8'
        self.text.setText(texts)
    def button_nine(self):
        global texts
        texts+='9'
        self.text.setText(texts)
    def button_zero(self):
        global texts
        texts+='0'
        self.text.setText(texts)


    def button_up(self):
        print('up');
        
    def button_right(self):
        print('right');
        
    def button_left(self):
        print('left');
        
    def button_down(self):
        print('down');
        
    def button_dot(self):
        texts+='.'
        self.text.setText(texts)
    def button_enter(self):
        texts+=' '
        self.text.setText(texts)
    def button_shift(self):
        if self.flag=='0':
            self.flag='2';
        elif self.flag=='1':
            self.flag='3';

    def button_alt(self):
        self.flag='4'
    def button_f4(self):
        if self.flag=='4':
            os.system('TASKKILL /F /IM python.exe');
    
            
            
        



if __name__ == "__main__":
    import sys
    app = QtWidgets.QApplication(sys.argv)
    MainWindow = QtWidgets.QMainWindow()
    ui = Ui_MainWindow()
    ui.setupUi(MainWindow)
    MainWindow.show()
    sys.exit(app.exec_())

