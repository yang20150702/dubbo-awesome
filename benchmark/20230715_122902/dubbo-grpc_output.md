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
# Warmup Iteration   1: 4.504 ops/ms
# Warmup Iteration   2: 9.550 ops/ms
# Warmup Iteration   3: 10.511 ops/ms
Iteration   1: 10.996 ops/ms
Iteration   2: 10.763 ops/ms
Iteration   3: 10.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.891 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (10.763, 10.891, 10.996), stdev = 0.119
  CI (99.9%): [8.727, 13.054] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.146 ops/ms
# Warmup Iteration   2: 10.698 ops/ms
# Warmup Iteration   3: 11.049 ops/ms
Iteration   1: 11.486 ops/ms
Iteration   2: 11.479 ops/ms
Iteration   3: 11.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.457 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (11.407, 11.457, 11.486), stdev = 0.044
  CI (99.9%): [10.653, 12.262] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.996 ops/ms
# Warmup Iteration   2: 10.077 ops/ms
# Warmup Iteration   3: 10.671 ops/ms
Iteration   1: 10.743 ops/ms
Iteration   2: 10.654 ops/ms
Iteration   3: 10.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.757 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (10.654, 10.757, 10.873), stdev = 0.110
  CI (99.9%): [8.744, 12.769] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.561 ops/ms
# Warmup Iteration   2: 7.972 ops/ms
# Warmup Iteration   3: 8.150 ops/ms
Iteration   1: 8.232 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 8.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.231 ±(99.9%) 0.199 ops/ms [Average]
  (min, avg, max) = (8.219, 8.231, 8.241), stdev = 0.011
  CI (99.9%): [8.032, 8.430] (assumes normal distribution)


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 2.923 ±(99.9%) 0.003 ms/op
Iteration   2: 2.989 ±(99.9%) 0.002 ms/op
Iteration   3: 3.027 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.980 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (2.923, 2.980, 3.027), stdev = 0.052
  CI (99.9%): [2.026, 3.934] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.003 ms/op
Iteration   1: 2.873 ±(99.9%) 0.002 ms/op
Iteration   2: 2.734 ±(99.9%) 0.003 ms/op
Iteration   3: 2.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.832 ±(99.9%) 1.545 ms/op [Average]
  (min, avg, max) = (2.734, 2.832, 2.888), stdev = 0.085
  CI (99.9%): [1.287, 4.376] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.003 ms/op
Iteration   2: 3.036 ±(99.9%) 0.002 ms/op
Iteration   3: 2.955 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.989 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (2.955, 2.989, 3.036), stdev = 0.042
  CI (99.9%): [2.216, 3.762] (assumes normal distribution)


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
# Warmup Iteration   1: 4.758 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.041 ms/op
Iteration   1: 3.822 ±(99.9%) 0.035 ms/op
Iteration   2: 3.874 ±(99.9%) 0.009 ms/op
Iteration   3: 3.837 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.845 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (3.822, 3.845, 3.874), stdev = 0.027
  CI (99.9%): [3.350, 4.339] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
Iteration   1: 2.946 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.601 ms/op
                 createUser·p0.9999: 12.047 ms/op
                 createUser·p1.00:   12.272 ms/op

Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.868 ms/op
                 createUser·p0.9999: 19.239 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.082 ms/op
                 createUser·p0.9999: 16.351 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326453
  mean =      2.939 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2258 
    [ 1.250,  2.500) = 35624 
    [ 2.500,  3.750) = 273701 
    [ 3.750,  5.000) = 13548 
    [ 5.000,  6.250) = 742 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =     17.433 ms/op
     p(99.9990) =     19.554 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.005 ms/op
Iteration   1: 2.827 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  5.897 ms/op
                 existUser·p0.9999: 12.006 ms/op
                 existUser·p1.00:   12.354 ms/op

Iteration   2: 2.807 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.364 ms/op
                 existUser·p0.9999: 19.156 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   3: 2.820 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.111 ms/op
                 existUser·p0.9999: 15.565 ms/op
                 existUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340607
  mean =      2.818 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56724 
    [ 2.500,  5.000) = 282619 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     15.630 ms/op
     p(99.9990) =     20.205 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.946 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.720 ms/op
                 getUser·p0.9999: 11.702 ms/op
                 getUser·p1.00:   12.108 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.566 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.385 ms/op
                 getUser·p0.999:  8.097 ms/op
                 getUser·p0.9999: 25.637 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323611
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28506 
    [ 2.500,  5.000) = 293529 
    [ 5.000,  7.500) = 1209 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.977 ms/op
     p(99.9900) =     24.230 ms/op
     p(99.9990) =     25.912 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 5.327 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.009 ms/op
Iteration   1: 3.872 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.275 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.131 ms/op
                 listUser·p0.9999: 18.570 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  15.343 ms/op
                 listUser·p0.9999: 19.683 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 3.837 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.571 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.573 ms/op
                 listUser·p0.999:  14.181 ms/op
                 listUser·p0.9999: 16.706 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247575
  mean =      3.875 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4331 
    [ 2.500,  5.000) = 223285 
    [ 5.000,  7.500) = 18956 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.275 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     18.587 ms/op
     p(99.9990) =     20.694 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.891 ± 2.164  ops/ms
ClientGrpc.existUser                       thrpt       3  11.457 ± 0.805  ops/ms
ClientGrpc.getUser                         thrpt       3  10.757 ± 2.012  ops/ms
ClientGrpc.listUser                        thrpt       3   8.231 ± 0.199  ops/ms
ClientGrpc.createUser                       avgt       3   2.980 ± 0.954   ms/op
ClientGrpc.existUser                        avgt       3   2.832 ± 1.545   ms/op
ClientGrpc.getUser                          avgt       3   2.989 ± 0.773   ms/op
ClientGrpc.listUser                         avgt       3   3.845 ± 0.494   ms/op
ClientGrpc.createUser                     sample  326453   2.939 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.504           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.433           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.628           ms/op
ClientGrpc.existUser                      sample  340607   2.818 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.495           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.021           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.630           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.480           ms/op
ClientGrpc.getUser                        sample  323611   2.969 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.977           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.230           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.018           ms/op
ClientGrpc.listUser                       sample  247575   3.875 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.275           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.664           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.587           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.742           ms/op
