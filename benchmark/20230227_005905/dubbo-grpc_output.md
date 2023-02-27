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
# Warmup Iteration   1: 5.449 ops/ms
# Warmup Iteration   2: 9.293 ops/ms
# Warmup Iteration   3: 10.560 ops/ms
Iteration   1: 10.792 ops/ms
Iteration   2: 10.917 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.752 ±(99.9%) 3.417 ops/ms [Average]
  (min, avg, max) = (10.549, 10.752, 10.917), stdev = 0.187
  CI (99.9%): [7.336, 14.169] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.209 ops/ms
# Warmup Iteration   2: 10.562 ops/ms
# Warmup Iteration   3: 11.283 ops/ms
Iteration   1: 10.820 ops/ms
Iteration   2: 11.060 ops/ms
Iteration   3: 11.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.986 ±(99.9%) 2.626 ops/ms [Average]
  (min, avg, max) = (10.820, 10.986, 11.078), stdev = 0.144
  CI (99.9%): [8.360, 13.612] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.282 ops/ms
# Warmup Iteration   2: 10.511 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.468 ops/ms
Iteration   2: 10.859 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.613 ±(99.9%) 3.911 ops/ms [Average]
  (min, avg, max) = (10.468, 10.613, 10.859), stdev = 0.214
  CI (99.9%): [6.703, 14.524] (assumes normal distribution)


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
# Warmup Iteration   1: 5.957 ops/ms
# Warmup Iteration   2: 7.731 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 7.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.968 ±(99.9%) 0.954 ops/ms [Average]
  (min, avg, max) = (7.936, 7.968, 8.029), stdev = 0.052
  CI (99.9%): [7.014, 8.922] (assumes normal distribution)


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.002 ms/op
Iteration   1: 3.095 ±(99.9%) 0.006 ms/op
Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.083 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.065, 3.083, 3.095), stdev = 0.016
  CI (99.9%): [2.796, 3.370] (assumes normal distribution)


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.851 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.002 ms/op
Iteration   1: 2.946 ±(99.9%) 0.002 ms/op
Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
Iteration   3: 2.968 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.946, 2.959, 2.968), stdev = 0.012
  CI (99.9%): [2.744, 3.174] (assumes normal distribution)


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.040 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.009, 3.040, 3.061), stdev = 0.028
  CI (99.9%): [2.529, 3.552] (assumes normal distribution)


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
# Warmup Iteration   1: 5.216 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.010 ms/op
Iteration   1: 4.009 ±(99.9%) 0.022 ms/op
Iteration   2: 4.113 ±(99.9%) 0.017 ms/op
Iteration   3: 4.008 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.043 ±(99.9%) 1.102 ms/op [Average]
  (min, avg, max) = (4.008, 4.043, 4.113), stdev = 0.060
  CI (99.9%): [2.942, 5.145] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.369 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  5.702 ms/op
                 createUser·p0.9999: 11.245 ms/op
                 createUser·p1.00:   11.583 ms/op

Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.922 ms/op
                 createUser·p0.9999: 12.730 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  10.174 ms/op
                 createUser·p0.9999: 23.349 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314730
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32838 
    [ 2.500,  5.000) = 280768 
    [ 5.000,  7.500) = 762 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.369 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.061 ms/op
     p(99.9900) =     22.594 ms/op
     p(99.9990) =     23.490 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  5.792 ms/op
                 existUser·p0.9999: 12.688 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   2: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.798 ms/op
                 existUser·p0.9999: 12.924 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.931 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  7.362 ms/op
                 existUser·p0.9999: 26.186 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331711
  mean =      2.895 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54425 
    [ 2.500,  5.000) = 276467 
    [ 5.000,  7.500) = 586 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.556 ms/op
     p(99.9900) =     14.226 ms/op
     p(99.9990) =     26.532 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.484 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.334 ms/op
                 getUser·p0.9999: 11.305 ms/op
                 getUser·p1.00:   11.485 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.640 ms/op
                 getUser·p0.9999: 11.619 ms/op
                 getUser·p1.00:   11.960 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.276 ms/op
                 getUser·p0.9999: 17.993 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314548
  mean =      3.049 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1489 
    [ 1.250,  2.500) = 28410 
    [ 2.500,  3.750) = 262054 
    [ 3.750,  5.000) = 21639 
    [ 5.000,  6.250) = 504 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.564 ms/op
     p(99.9900) =     16.542 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 5.198 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.012 ms/op
Iteration   1: 3.989 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  11.862 ms/op
                 listUser·p0.9999: 14.647 ms/op
                 listUser·p1.00:   15.024 ms/op

Iteration   2: 3.882 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.191 ms/op
                 listUser·p0.9999: 15.766 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 22.344 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243131
  mean =      3.945 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3581 
    [ 2.500,  5.000) = 217262 
    [ 5.000,  7.500) = 21298 
    [ 7.500, 10.000) = 610 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     21.944 ms/op
     p(99.9990) =     22.629 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.752 ± 3.417  ops/ms
ClientGrpc.existUser                       thrpt       3  10.986 ± 2.626  ops/ms
ClientGrpc.getUser                         thrpt       3  10.613 ± 3.911  ops/ms
ClientGrpc.listUser                        thrpt       3   7.968 ± 0.954  ops/ms
ClientGrpc.createUser                       avgt       3   3.083 ± 0.287   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 0.215   ms/op
ClientGrpc.getUser                          avgt       3   3.040 ± 0.511   ms/op
ClientGrpc.listUser                         avgt       3   4.043 ± 1.102   ms/op
ClientGrpc.createUser                     sample  314730   3.051 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.369           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.061           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.594           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.313           ms/op
ClientGrpc.existUser                      sample  331711   2.895 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.556           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.226           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.673           ms/op
ClientGrpc.getUser                        sample  314548   3.049 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.484           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.564           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.542           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.743           ms/op
ClientGrpc.listUser                       sample  243131   3.945 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.847           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.747           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.944           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
