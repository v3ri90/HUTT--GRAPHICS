#include <GL/glut.h>

void display() {
    glClear(GL_COLOR_BUFFER_BIT);

    
    glBegin(GL_QUADS);
        
        glColor3f(1.0, 0.0, 0.0); 
        glVertex2f(-0.51, -0.51);
        glVertex2f(0.51, -0.51);
        glVertex2f(0.51, 0.51);
        glVertex2f(-0.51, 0.51);

        glColor3f(0.0, 1.0, 0.0); 
        glVertex2f(-0.5, -0.5);
        glVertex2f(0.5, -0.5);
        glVertex2f(0.5, 0.5);
        glVertex2f(-0.5, 0.5);
        
        glColor3f(0.0, 0.0, 1.0); 
        glVertex2f(-0.5, -0.5);
        glVertex2f(-0.51, -0.5);
        glVertex2f(-0.51, 0.5);
        glVertex2f(-0.5, 0.5);
    glEnd();

    
    glBegin(GL_TRIANGLES);
        glColor3f(0.8, 0.0, 0.0); 
        glVertex2f(-0.5, 0.5);
        glColor3f(0.0, 0.8, 0.0); 
        glVertex2f(0.5, 0.5);
        glColor3f(0.0, 0.0, 0.8); 
        glVertex2f(0.0, 1.0);
    glEnd();

    glFlush();
}

int main(int argc, char** argv) {
    glutInit(&argc, argv);
    glutCreateWindow("Colored Hut");
    glutInitWindowSize(400, 400);
    glutDisplayFunc(display);
    glClearColor(0.0, 0.0, 0.0, 1.0); 
    glutMainLoop();
    return 0;
}