# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.128 ops/ms
# Warmup Iteration   2: 9.604 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 10.242 ops/ms
Iteration   3: 10.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.392 ±(99.9%) 4.835 ops/ms [Average]
  (min, avg, max) = (10.236, 10.392, 10.698), stdev = 0.265
  CI (99.9%): [5.557, 15.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.632 ops/ms
# Warmup Iteration   2: 10.651 ops/ms
# Warmup Iteration   3: 11.674 ops/ms
Iteration   1: 10.909 ops/ms
Iteration   2: 10.949 ops/ms
Iteration   3: 11.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.015 ±(99.9%) 2.748 ops/ms [Average]
  (min, avg, max) = (10.909, 11.015, 11.188), stdev = 0.151
  CI (99.9%): [8.267, 13.763] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.672 ops/ms
# Warmup Iteration   2: 10.151 ops/ms
# Warmup Iteration   3: 10.597 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 10.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.548 ±(99.9%) 1.981 ops/ms [Average]
  (min, avg, max) = (10.444, 10.548, 10.661), stdev = 0.109
  CI (99.9%): [8.567, 12.529] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.029 ops/ms
# Warmup Iteration   2: 7.842 ops/ms
# Warmup Iteration   3: 8.082 ops/ms
Iteration   1: 7.790 ops/ms
Iteration   2: 8.205 ops/ms
Iteration   3: 8.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.111 ±(99.9%) 5.204 ops/ms [Average]
  (min, avg, max) = (7.790, 8.111, 8.337), stdev = 0.285
  CI (99.9%): [2.907, 13.315] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.121 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.001 ms/op
Iteration   3: 3.121 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.147 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (3.121, 3.147, 3.199), stdev = 0.045
  CI (99.9%): [2.324, 3.971] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.824 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.003 ms/op
Iteration   1: 2.950 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 2.942 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.940, 2.944, 2.950), stdev = 0.005
  CI (99.9%): [2.844, 3.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 3.058 ±(99.9%) 0.003 ms/op
Iteration   2: 3.063 ±(99.9%) 0.002 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.037 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (2.990, 3.037, 3.063), stdev = 0.041
  CI (99.9%): [2.296, 3.778] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.293 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.063 ms/op
Iteration   1: 3.853 ±(99.9%) 0.029 ms/op
Iteration   2: 3.956 ±(99.9%) 0.019 ms/op
Iteration   3: 3.944 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.853, 3.918, 3.956), stdev = 0.056
  CI (99.9%): [2.892, 4.943] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.560 ms/op
                 createUser·p0.9999: 12.335 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  7.389 ms/op
                 createUser·p0.9999: 14.150 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.067 ms/op
                 createUser·p0.9999: 15.899 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314464
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2483 
    [ 1.250,  2.500) = 23313 
    [ 2.500,  3.750) = 264590 
    [ 3.750,  5.000) = 22977 
    [ 5.000,  6.250) = 561 
    [ 6.250,  7.500) = 242 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.882 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     14.784 ms/op
     p(99.9990) =     17.624 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.958 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.006 ms/op
Iteration   1: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  7.329 ms/op
                 existUser·p0.9999: 11.140 ms/op
                 existUser·p1.00:   11.469 ms/op

Iteration   2: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  5.899 ms/op
                 existUser·p0.9999: 15.072 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  11.140 ms/op
                 existUser·p0.9999: 14.832 ms/op
                 existUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328383
  mean =      2.923 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2155 
    [ 1.250,  2.500) = 49075 
    [ 2.500,  3.750) = 265869 
    [ 3.750,  5.000) = 10364 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     14.814 ms/op
     p(99.9990) =     15.277 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.025 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.328 ms/op
                 getUser·p0.9999: 15.803 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  6.651 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313028
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1678 
    [ 1.250,  2.500) = 26541 
    [ 2.500,  3.750) = 256883 
    [ 3.750,  5.000) = 27106 
    [ 5.000,  6.250) = 358 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     15.802 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.086 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
Iteration   1: 4.017 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.271 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.579 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   2: 3.880 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.718 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  18.357 ms/op
                 listUser·p0.9999: 24.102 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   3: 4.038 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.223 ms/op
                 listUser·p0.9999: 27.276 ms/op
                 listUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241208
  mean =      3.977 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5033 
    [ 2.500,  5.000) = 207747 
    [ 5.000,  7.500) = 27257 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.271 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.815 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     24.597 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.392 ± 4.835  ops/ms
ClientGrpc.existUser                       thrpt       3  11.015 ± 2.748  ops/ms
ClientGrpc.getUser                         thrpt       3  10.548 ± 1.981  ops/ms
ClientGrpc.listUser                        thrpt       3   8.111 ± 5.204  ops/ms
ClientGrpc.createUser                       avgt       3   3.147 ± 0.824   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.100   ms/op
ClientGrpc.getUser                          avgt       3   3.037 ± 0.741   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 1.026   ms/op
ClientGrpc.createUser                     sample  314464   3.053 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.530           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.389           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.784           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.662           ms/op
ClientGrpc.existUser                      sample  328383   2.923 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.332           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.814           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.335           ms/op
ClientGrpc.getUser                        sample  313028   3.067 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.963           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.802           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.007           ms/op
ClientGrpc.listUser                       sample  241208   3.977 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.271           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.815           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.597           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.754           ms/op
