# MATLAB-utilities
Handy engineering functions for MATLAB

#### `plotcube` example

```
figure;
hold on;
plotcube([0 0 0],1,2,0.1,0,20,0,123);
plotcube([2 0 2],1,2,3,0,0,140,55);
axis equal;
grid on;
xlabel('X','FontSize',18);
ylabel('Y','FontSize',18)
zlabel('Z','FontSize',18)
h = gca;
view(120,30);
colormap jet;
colorbar;
hold off;
```

