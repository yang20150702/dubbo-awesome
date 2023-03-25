# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.413 ops/ms
# Warmup Iteration   2: 9.446 ops/ms
# Warmup Iteration   3: 10.620 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.904 ops/ms
Iteration   3: 11.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.800 ±(99.9%) 4.948 ops/ms [Average]
  (min, avg, max) = (10.493, 10.800, 11.005), stdev = 0.271
  CI (99.9%): [5.852, 15.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 8.285 ops/ms
# Warmup Iteration   2: 10.955 ops/ms
# Warmup Iteration   3: 11.904 ops/ms
Iteration   1: 11.558 ops/ms
Iteration   2: 11.443 ops/ms
Iteration   3: 11.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.614 ±(99.9%) 3.737 ops/ms [Average]
  (min, avg, max) = (11.443, 11.614, 11.841), stdev = 0.205
  CI (99.9%): [7.877, 15.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.475 ops/ms
# Warmup Iteration   2: 10.638 ops/ms
# Warmup Iteration   3: 10.981 ops/ms
Iteration   1: 10.863 ops/ms
Iteration   2: 10.954 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.881 ±(99.9%) 1.211 ops/ms [Average]
  (min, avg, max) = (10.825, 10.881, 10.954), stdev = 0.066
  CI (99.9%): [9.670, 12.091] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.788 ops/ms
# Warmup Iteration   2: 7.929 ops/ms
# Warmup Iteration   3: 8.241 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 8.133 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.191 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (8.133, 8.191, 8.277), stdev = 0.076
  CI (99.9%): [6.797, 9.585] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.004 ms/op
Iteration   1: 2.916 ±(99.9%) 0.003 ms/op
Iteration   2: 2.919 ±(99.9%) 0.003 ms/op
Iteration   3: 2.925 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.920 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.916, 2.920, 2.925), stdev = 0.004
  CI (99.9%): [2.839, 3.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.661 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.924 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.813 ±(99.9%) 0.003 ms/op
Iteration   1: 2.826 ±(99.9%) 0.003 ms/op
Iteration   2: 2.819 ±(99.9%) 0.002 ms/op
Iteration   3: 2.807 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.818 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.807, 2.818, 2.826), stdev = 0.010
  CI (99.9%): [2.637, 2.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.009 ms/op
Iteration   1: 2.932 ±(99.9%) 0.002 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 2.999 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.957 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (2.932, 2.957, 2.999), stdev = 0.037
  CI (99.9%): [2.287, 3.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.287 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.013 ms/op
Iteration   1: 3.952 ±(99.9%) 0.029 ms/op
Iteration   2: 3.935 ±(99.9%) 0.022 ms/op
Iteration   3: 3.972 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.953 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.935, 3.953, 3.972), stdev = 0.019
  CI (99.9%): [3.613, 4.294] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 18.350 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.417 ms/op
                 createUser·p0.999:  8.386 ms/op
                 createUser·p0.9999: 17.732 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   3: 2.922 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  9.611 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326615
  mean =      2.938 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38826 
    [ 2.500,  5.000) = 286314 
    [ 5.000,  7.500) = 1035 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.198 ms/op
     p(99.9900) =     23.571 ms/op
     p(99.9990) =     25.255 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.907 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.873 ±(99.9%) 0.006 ms/op
Iteration   1: 2.826 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.095 ms/op
                 existUser·p0.9999: 16.865 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   2: 2.767 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.789 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  5.745 ms/op
                 existUser·p0.9999: 14.219 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.789 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.798 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.732 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 343406
  mean =      2.794 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3733 
    [ 1.250,  2.500) = 64882 
    [ 2.500,  3.750) = 263595 
    [ 3.750,  5.000) = 10241 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 144 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.485 ms/op
     p(99.9900) =     14.636 ms/op
     p(99.9990) =     17.109 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.942 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.961 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.229 ms/op
                 getUser·p0.999:  5.948 ms/op
                 getUser·p0.9999: 10.407 ms/op
                 getUser·p1.00:   10.928 ms/op

Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.493 ms/op
                 getUser·p0.9999: 15.829 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.295 ms/op
                 getUser·p0.999:  7.516 ms/op
                 getUser·p0.9999: 14.336 ms/op
                 getUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326116
  mean =      2.943 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2345 
    [ 1.250,  2.500) = 33849 
    [ 2.500,  3.750) = 275364 
    [ 3.750,  5.000) = 13585 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 250 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.749 ms/op
     p(99.9900) =     14.257 ms/op
     p(99.9990) =     16.003 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.010 ms/op
Iteration   1: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.580 ms/op
                 listUser·p0.999:  12.491 ms/op
                 listUser·p0.9999: 19.814 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.793 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.314 ms/op
                 listUser·p0.9999: 20.900 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  17.530 ms/op
                 listUser·p0.9999: 25.552 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248531
  mean =      3.866 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5977 
    [ 2.500,  5.000) = 220883 
    [ 5.000,  7.500) = 20426 
    [ 7.500, 10.000) = 716 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.220 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     25.822 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.800 ± 4.948  ops/ms
ClientGrpc.existUser                       thrpt       3  11.614 ± 3.737  ops/ms
ClientGrpc.getUser                         thrpt       3  10.881 ± 1.211  ops/ms
ClientGrpc.listUser                        thrpt       3   8.191 ± 1.394  ops/ms
ClientGrpc.createUser                       avgt       3   2.920 ± 0.081   ms/op
ClientGrpc.existUser                        avgt       3   2.818 ± 0.180   ms/op
ClientGrpc.getUser                          avgt       3   2.957 ± 0.670   ms/op
ClientGrpc.listUser                         avgt       3   3.953 ± 0.340   ms/op
ClientGrpc.createUser                     sample  326615   2.938 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.663           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.925           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.441           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.198           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.571           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.362           ms/op
ClientGrpc.existUser                      sample  343406   2.794 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.648           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.802           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.485           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.636           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.317           ms/op
ClientGrpc.getUser                        sample  326116   2.943 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.552           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.749           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.257           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.040           ms/op
ClientGrpc.listUser                       sample  248531   3.866 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.908           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.220           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.084           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919           ms/op
