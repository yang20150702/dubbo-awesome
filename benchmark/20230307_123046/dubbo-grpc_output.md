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
# Warmup Iteration   1: 4.629 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 9.829 ops/ms
Iteration   1: 10.569 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.329 ±(99.9%) 5.879 ops/ms [Average]
  (min, avg, max) = (9.963, 10.329, 10.569), stdev = 0.322
  CI (99.9%): [4.449, 16.208] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.421 ops/ms
# Warmup Iteration   2: 10.213 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.653 ops/ms
Iteration   2: 10.161 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.470 ±(99.9%) 4.902 ops/ms [Average]
  (min, avg, max) = (10.161, 10.470, 10.653), stdev = 0.269
  CI (99.9%): [5.567, 15.372] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.621 ops/ms
# Warmup Iteration   2: 9.620 ops/ms
# Warmup Iteration   3: 9.884 ops/ms
Iteration   1: 9.853 ops/ms
Iteration   2: 9.837 ops/ms
Iteration   3: 9.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.882 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (9.837, 9.882, 9.956), stdev = 0.064
  CI (99.9%): [8.707, 11.057] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.628 ops/ms
# Warmup Iteration   2: 7.368 ops/ms
# Warmup Iteration   3: 7.864 ops/ms
Iteration   1: 7.808 ops/ms
Iteration   2: 7.773 ops/ms
Iteration   3: 7.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.845 ±(99.9%) 1.732 ops/ms [Average]
  (min, avg, max) = (7.773, 7.845, 7.952), stdev = 0.095
  CI (99.9%): [6.112, 9.577] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.370 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.009 ms/op
Iteration   1: 3.159 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.003 ms/op
Iteration   3: 3.217 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.182 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.159, 3.182, 3.217), stdev = 0.031
  CI (99.9%): [2.616, 3.749] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.915 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.002 ms/op
Iteration   1: 3.113 ±(99.9%) 0.002 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.075 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.055, 3.075, 3.113), stdev = 0.033
  CI (99.9%): [2.480, 3.671] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.002 ms/op
Iteration   1: 3.222 ±(99.9%) 0.003 ms/op
Iteration   2: 3.217 ±(99.9%) 0.003 ms/op
Iteration   3: 3.181 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.207 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (3.181, 3.207, 3.222), stdev = 0.022
  CI (99.9%): [2.798, 3.615] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.891 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.022 ms/op
Iteration   1: 4.260 ±(99.9%) 0.014 ms/op
Iteration   2: 4.115 ±(99.9%) 0.010 ms/op
Iteration   3: 4.223 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.199 ±(99.9%) 1.377 ms/op [Average]
  (min, avg, max) = (4.115, 4.199, 4.260), stdev = 0.075
  CI (99.9%): [2.822, 5.577] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
Iteration   1: 3.163 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  8.529 ms/op
                 createUser·p0.9999: 26.407 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.542 ms/op
                 createUser·p0.9999: 33.356 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  14.192 ms/op
                 createUser·p0.9999: 20.671 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299711
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18074 
    [ 2.500,  5.000) = 280154 
    [ 5.000,  7.500) = 1053 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     32.769 ms/op
     p(99.9990) =     33.687 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.082 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.435 ms/op
                 existUser·p0.9999: 13.176 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.418 ms/op
                 existUser·p0.9999: 14.547 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 16.791 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314600
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1075 
    [ 1.250,  2.500) = 40031 
    [ 2.500,  3.750) = 243976 
    [ 3.750,  5.000) = 28692 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 177 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      8.877 ms/op
     p(99.9900) =     14.967 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.234 ms/op
                 getUser·p0.9999: 12.954 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   2: 3.150 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.115 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.431 ms/op
                 getUser·p0.9999: 15.377 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.325 ms/op
                 getUser·p0.9999: 16.700 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306835
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 585 
    [ 1.250,  2.500) = 24300 
    [ 2.500,  3.750) = 248765 
    [ 3.750,  5.000) = 32029 
    [ 5.000,  6.250) = 609 
    [ 6.250,  7.500) = 261 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     15.810 ms/op
     p(99.9990) =     17.229 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 5.083 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.012 ms/op
Iteration   1: 4.134 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 26.321 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   2: 4.029 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.589 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   3: 4.162 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.229 ms/op
                 listUser·p0.999:  18.889 ms/op
                 listUser·p0.9999: 25.381 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233691
  mean =      4.108 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2904 
    [ 2.500,  5.000) = 200371 
    [ 5.000,  7.500) = 28852 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     17.869 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     28.748 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.329 ± 5.879  ops/ms
ClientGrpc.existUser                       thrpt       3  10.470 ± 4.902  ops/ms
ClientGrpc.getUser                         thrpt       3   9.882 ± 1.175  ops/ms
ClientGrpc.listUser                        thrpt       3   7.845 ± 1.732  ops/ms
ClientGrpc.createUser                       avgt       3   3.182 ± 0.566   ms/op
ClientGrpc.existUser                        avgt       3   3.075 ± 0.596   ms/op
ClientGrpc.getUser                          avgt       3   3.207 ± 0.408   ms/op
ClientGrpc.listUser                         avgt       3   4.199 ± 1.377   ms/op
ClientGrpc.createUser                     sample  299711   3.203 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.775           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.782           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.769           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.406           ms/op
ClientGrpc.existUser                      sample  314600   3.050 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.710           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.877           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.967           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.007           ms/op
ClientGrpc.getUser                        sample  306835   3.129 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.681           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.348           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.810           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.367           ms/op
ClientGrpc.listUser                       sample  233691   4.108 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.879           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.869           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.116           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.836           ms/op
