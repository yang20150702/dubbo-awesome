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
# Warmup Iteration   1: 4.608 ops/ms
# Warmup Iteration   2: 10.090 ops/ms
# Warmup Iteration   3: 10.509 ops/ms
Iteration   1: 10.820 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.539 ±(99.9%) 4.759 ops/ms [Average]
  (min, avg, max) = (10.305, 10.539, 10.820), stdev = 0.261
  CI (99.9%): [5.780, 15.297] (assumes normal distribution)


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
# Warmup Iteration   1: 7.836 ops/ms
# Warmup Iteration   2: 10.720 ops/ms
# Warmup Iteration   3: 10.816 ops/ms
Iteration   1: 10.907 ops/ms
Iteration   2: 10.784 ops/ms
Iteration   3: 11.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.926 ±(99.9%) 2.791 ops/ms [Average]
  (min, avg, max) = (10.784, 10.926, 11.088), stdev = 0.153
  CI (99.9%): [8.135, 13.717] (assumes normal distribution)


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
# Warmup Iteration   1: 7.791 ops/ms
# Warmup Iteration   2: 10.291 ops/ms
# Warmup Iteration   3: 10.638 ops/ms
Iteration   1: 10.417 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.506 ±(99.9%) 3.751 ops/ms [Average]
  (min, avg, max) = (10.359, 10.506, 10.741), stdev = 0.206
  CI (99.9%): [6.755, 14.257] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.122 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 7.959 ops/ms
Iteration   1: 8.102 ops/ms
Iteration   2: 8.076 ops/ms
Iteration   3: 8.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.216 ±(99.9%) 4.011 ops/ms [Average]
  (min, avg, max) = (8.076, 8.216, 8.469), stdev = 0.220
  CI (99.9%): [4.204, 12.227] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.051 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 3.013 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.029 ±(99.9%) 1.821 ms/op [Average]
  (min, avg, max) = (2.937, 3.029, 3.135), stdev = 0.100
  CI (99.9%): [1.208, 4.849] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.004 ms/op
Iteration   1: 2.891 ±(99.9%) 0.002 ms/op
Iteration   2: 2.948 ±(99.9%) 0.002 ms/op
Iteration   3: 2.866 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (2.866, 2.902, 2.948), stdev = 0.042
  CI (99.9%): [2.126, 3.677] (assumes normal distribution)


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.002 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.029 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (3.004, 3.029, 3.055), stdev = 0.025
  CI (99.9%): [2.564, 3.494] (assumes normal distribution)


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
# Warmup Iteration   1: 5.095 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
Iteration   1: 3.936 ±(99.9%) 0.028 ms/op
Iteration   2: 3.953 ±(99.9%) 0.023 ms/op
Iteration   3: 3.890 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.927 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.890, 3.927, 3.953), stdev = 0.033
  CI (99.9%): [3.329, 4.525] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.272 ms/op
                 createUser·p0.9999: 12.346 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.373 ms/op
                 createUser·p0.9999: 15.691 ms/op
                 createUser·p1.00:   16.040 ms/op

Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.684 ms/op
                 createUser·p0.9999: 15.577 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312830
  mean =      3.068 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1202 
    [ 1.250,  2.500) = 26696 
    [ 2.500,  3.750) = 259136 
    [ 3.750,  5.000) = 24793 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 196 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.227 ms/op
     p(99.9900) =     15.499 ms/op
     p(99.9990) =     16.036 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  6.914 ms/op
                 existUser·p0.9999: 19.530 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   2: 2.922 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  11.728 ms/op
                 existUser·p0.9999: 16.107 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   3: 2.891 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  9.820 ms/op
                 existUser·p0.9999: 16.992 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327904
  mean =      2.929 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3718 
    [ 1.250,  2.500) = 48103 
    [ 2.500,  3.750) = 259830 
    [ 3.750,  5.000) = 15192 
    [ 5.000,  6.250) = 358 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      9.521 ms/op
     p(99.9900) =     18.095 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 11.764 ms/op
                 getUser·p1.00:   12.173 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 13.508 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.345 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.137 ms/op
                 getUser·p0.9999: 18.557 ms/op
                 getUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318205
  mean =      3.015 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1719 
    [ 1.250,  2.500) = 28086 
    [ 2.500,  3.750) = 269844 
    [ 3.750,  5.000) = 17486 
    [ 5.000,  6.250) = 516 
    [ 6.250,  7.500) = 295 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     18.862 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
Iteration   1: 3.927 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.673 ms/op
                 listUser·p0.9999: 19.848 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 3.848 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.717 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.316 ms/op
                 listUser·p0.9999: 20.972 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  12.608 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245036
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5954 
    [ 2.500,  5.000) = 213919 
    [ 5.000,  7.500) = 24069 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.516 ms/op
     p(99.9900) =     20.595 ms/op
     p(99.9990) =     21.284 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.539 ± 4.759  ops/ms
ClientGrpc.existUser                       thrpt       3  10.926 ± 2.791  ops/ms
ClientGrpc.getUser                         thrpt       3  10.506 ± 3.751  ops/ms
ClientGrpc.listUser                        thrpt       3   8.216 ± 4.011  ops/ms
ClientGrpc.createUser                       avgt       3   3.029 ± 1.821   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 0.775   ms/op
ClientGrpc.getUser                          avgt       3   3.029 ± 0.465   ms/op
ClientGrpc.listUser                         avgt       3   3.927 ± 0.598   ms/op
ClientGrpc.createUser                     sample  312830   3.068 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.598           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.227           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.499           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.089           ms/op
ClientGrpc.existUser                      sample  327904   2.929 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.620           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.521           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.095           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  318205   3.015 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.345           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.037           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.876           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.940           ms/op
ClientGrpc.listUser                       sample  245036   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.820           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.595           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.365           ms/op
