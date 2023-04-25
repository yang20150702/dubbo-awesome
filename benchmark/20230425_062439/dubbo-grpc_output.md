# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ops/ms
# Warmup Iteration   2: 9.609 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.741 ops/ms
Iteration   2: 10.777 ops/ms
Iteration   3: 10.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.773 ±(99.9%) 0.545 ops/ms [Average]
  (min, avg, max) = (10.741, 10.773, 10.800), stdev = 0.030
  CI (99.9%): [10.228, 11.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.039 ops/ms
# Warmup Iteration   2: 10.935 ops/ms
# Warmup Iteration   3: 11.421 ops/ms
Iteration   1: 11.213 ops/ms
Iteration   2: 11.447 ops/ms
Iteration   3: 11.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.387 ±(99.9%) 2.788 ops/ms [Average]
  (min, avg, max) = (11.213, 11.387, 11.501), stdev = 0.153
  CI (99.9%): [8.599, 14.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.949 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 10.961 ops/ms
Iteration   1: 10.935 ops/ms
Iteration   2: 11.110 ops/ms
Iteration   3: 10.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.977 ±(99.9%) 2.148 ops/ms [Average]
  (min, avg, max) = (10.885, 10.977, 11.110), stdev = 0.118
  CI (99.9%): [8.829, 13.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.192 ops/ms
# Warmup Iteration   2: 8.186 ops/ms
# Warmup Iteration   3: 8.259 ops/ms
Iteration   1: 8.270 ops/ms
Iteration   2: 8.213 ops/ms
Iteration   3: 8.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.270 ±(99.9%) 1.048 ops/ms [Average]
  (min, avg, max) = (8.213, 8.270, 8.328), stdev = 0.057
  CI (99.9%): [7.222, 9.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.003 ms/op
Iteration   1: 2.945 ±(99.9%) 0.007 ms/op
Iteration   2: 2.941 ±(99.9%) 0.002 ms/op
Iteration   3: 2.904 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.930 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (2.904, 2.930, 2.945), stdev = 0.022
  CI (99.9%): [2.523, 3.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.848 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.827 ±(99.9%) 0.003 ms/op
Iteration   1: 2.837 ±(99.9%) 0.003 ms/op
Iteration   2: 2.811 ±(99.9%) 0.002 ms/op
Iteration   3: 2.806 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.818 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.806, 2.818, 2.837), stdev = 0.017
  CI (99.9%): [2.511, 3.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.003 ms/op
Iteration   1: 2.877 ±(99.9%) 0.003 ms/op
Iteration   2: 2.934 ±(99.9%) 0.002 ms/op
Iteration   3: 2.964 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.925 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (2.877, 2.925, 2.964), stdev = 0.044
  CI (99.9%): [2.122, 3.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.507 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.011 ms/op
Iteration   1: 3.867 ±(99.9%) 0.038 ms/op
Iteration   2: 3.851 ±(99.9%) 0.025 ms/op
Iteration   3: 3.864 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.861 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.851, 3.861, 3.867), stdev = 0.009
  CI (99.9%): [3.704, 4.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.363 ms/op
                 createUser·p0.9999: 13.255 ms/op
                 createUser·p1.00:   13.517 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  9.833 ms/op
                 createUser·p0.9999: 13.799 ms/op
                 createUser·p1.00:   15.008 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  12.156 ms/op
                 createUser·p0.9999: 15.425 ms/op
                 createUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320500
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 798 
    [ 1.250,  2.500) = 32273 
    [ 2.500,  3.750) = 274196 
    [ 3.750,  5.000) = 12011 
    [ 5.000,  6.250) = 587 
    [ 6.250,  7.500) = 256 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =     10.002 ms/op
     p(99.9900) =     14.614 ms/op
     p(99.9990) =     15.781 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.891 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.006 ms/op
Iteration   1: 2.839 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  9.704 ms/op
                 existUser·p0.9999: 17.990 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 2.818 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.947 ms/op
                 existUser·p0.9999: 12.910 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   3: 2.802 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.355 ms/op
                 existUser·p0.99:   4.165 ms/op
                 existUser·p0.999:  6.128 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340338
  mean =      2.820 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3251 
    [ 1.250,  2.500) = 49022 
    [ 2.500,  3.750) = 278454 
    [ 3.750,  5.000) = 8680 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 143 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.219 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     13.670 ms/op
     p(99.9990) =     18.140 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  9.327 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 2.947 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 12.703 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.922 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.786 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.521 ms/op
                 getUser·p0.9999: 24.461 ms/op
                 getUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326326
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34832 
    [ 2.500,  5.000) = 290419 
    [ 5.000,  7.500) = 735 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.750 ms/op
     p(99.9900) =     20.358 ms/op
     p(99.9990) =     25.500 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  12.042 ms/op
                 listUser·p0.9999: 13.398 ms/op
                 listUser·p1.00:   13.779 ms/op

Iteration   2: 3.827 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.731 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 3.892 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.341 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.538 ms/op
                 listUser·p0.9999: 20.472 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248926
  mean =      3.856 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6347 
    [ 2.500,  5.000) = 221781 
    [ 5.000,  7.500) = 19800 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.341 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     12.813 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     23.004 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.773 ± 0.545  ops/ms
ClientGrpc.existUser                       thrpt       3  11.387 ± 2.788  ops/ms
ClientGrpc.getUser                         thrpt       3  10.977 ± 2.148  ops/ms
ClientGrpc.listUser                        thrpt       3   8.270 ± 1.048  ops/ms
ClientGrpc.createUser                       avgt       3   2.930 ± 0.407   ms/op
ClientGrpc.existUser                        avgt       3   2.818 ± 0.307   ms/op
ClientGrpc.getUser                          avgt       3   2.925 ± 0.804   ms/op
ClientGrpc.listUser                         avgt       3   3.861 ± 0.157   ms/op
ClientGrpc.createUser                     sample  320500   2.994 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.550           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.002           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.614           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.531           ms/op
ClientGrpc.existUser                      sample  340338   2.820 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.570           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.219           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.930           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.670           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.464           ms/op
ClientGrpc.getUser                        sample  326326   2.940 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.920           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.358           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.592           ms/op
ClientGrpc.listUser                       sample  248926   3.856 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.341           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.813           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.546           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.036           ms/op
