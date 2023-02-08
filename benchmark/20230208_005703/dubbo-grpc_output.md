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
# Warmup Iteration   1: 3.060 ops/ms
# Warmup Iteration   2: 7.032 ops/ms
# Warmup Iteration   3: 8.281 ops/ms
Iteration   1: 8.685 ops/ms
Iteration   2: 8.386 ops/ms
Iteration   3: 8.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.512 ±(99.9%) 2.827 ops/ms [Average]
  (min, avg, max) = (8.386, 8.512, 8.685), stdev = 0.155
  CI (99.9%): [5.685, 11.339] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.138 ops/ms
# Warmup Iteration   2: 8.541 ops/ms
# Warmup Iteration   3: 8.823 ops/ms
Iteration   1: 9.273 ops/ms
Iteration   2: 9.102 ops/ms
Iteration   3: 9.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.216 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (9.102, 9.216, 9.273), stdev = 0.099
  CI (99.9%): [7.417, 11.015] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ops/ms
# Warmup Iteration   2: 8.523 ops/ms
# Warmup Iteration   3: 8.647 ops/ms
Iteration   1: 8.666 ops/ms
Iteration   2: 8.692 ops/ms
Iteration   3: 8.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.668 ±(99.9%) 0.419 ops/ms [Average]
  (min, avg, max) = (8.646, 8.668, 8.692), stdev = 0.023
  CI (99.9%): [8.249, 9.087] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.893 ops/ms
# Warmup Iteration   2: 6.597 ops/ms
# Warmup Iteration   3: 6.730 ops/ms
Iteration   1: 6.859 ops/ms
Iteration   2: 6.841 ops/ms
Iteration   3: 6.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.839 ±(99.9%) 0.382 ops/ms [Average]
  (min, avg, max) = (6.817, 6.839, 6.859), stdev = 0.021
  CI (99.9%): [6.457, 7.221] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.991 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.004 ms/op
Iteration   1: 3.566 ±(99.9%) 0.003 ms/op
Iteration   2: 3.587 ±(99.9%) 0.003 ms/op
Iteration   3: 3.614 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.589 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.566, 3.589, 3.614), stdev = 0.024
  CI (99.9%): [3.144, 4.034] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.003 ms/op
Iteration   1: 3.500 ±(99.9%) 0.003 ms/op
Iteration   2: 3.505 ±(99.9%) 0.002 ms/op
Iteration   3: 3.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.495 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.481, 3.495, 3.505), stdev = 0.012
  CI (99.9%): [3.272, 3.718] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.269 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.002 ms/op
Iteration   1: 3.665 ±(99.9%) 0.002 ms/op
Iteration   2: 3.806 ±(99.9%) 0.002 ms/op
Iteration   3: 3.634 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.702 ±(99.9%) 1.671 ms/op [Average]
  (min, avg, max) = (3.634, 3.702, 3.806), stdev = 0.092
  CI (99.9%): [2.031, 5.373] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.808 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 5.062 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.616 ±(99.9%) 0.010 ms/op
Iteration   1: 4.494 ±(99.9%) 0.014 ms/op
Iteration   2: 4.651 ±(99.9%) 0.041 ms/op
Iteration   3: 4.698 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.614 ±(99.9%) 1.950 ms/op [Average]
  (min, avg, max) = (4.494, 4.614, 4.698), stdev = 0.107
  CI (99.9%): [2.664, 6.564] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.626 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.009 ms/op
Iteration   1: 3.678 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   5.126 ms/op
                 createUser·p0.999:  8.864 ms/op
                 createUser·p0.9999: 18.295 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   2: 3.639 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  12.929 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.704 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  9.783 ms/op
                 createUser·p0.9999: 29.995 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261179
  mean =      3.674 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7149 
    [ 2.500,  5.000) = 249094 
    [ 5.000,  7.500) = 4342 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     10.401 ms/op
     p(99.9900) =     28.177 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 4.777 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.009 ms/op
Iteration   1: 3.443 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  8.428 ms/op
                 existUser·p0.9999: 14.919 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 3.487 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  8.573 ms/op
                 existUser·p0.9999: 16.430 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   3: 3.619 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  10.169 ms/op
                 existUser·p0.9999: 31.850 ms/op
                 existUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272898
  mean =      3.515 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15876 
    [ 2.500,  5.000) = 253767 
    [ 5.000,  7.500) = 2705 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     30.904 ms/op
     p(99.9990) =     32.375 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.160 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.008 ms/op
Iteration   1: 3.630 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.321 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  11.449 ms/op
                 getUser·p0.9999: 17.837 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 3.682 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  11.865 ms/op
                 getUser·p0.9999: 19.976 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   3: 3.674 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.674 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  8.338 ms/op
                 getUser·p0.9999: 24.913 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262219
  mean =      3.662 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8306 
    [ 2.500,  5.000) = 248226 
    [ 5.000,  7.500) = 4899 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.321 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     27.210 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 6.506 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.883 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.552 ±(99.9%) 0.012 ms/op
Iteration   1: 4.678 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  15.852 ms/op
                 listUser·p0.9999: 22.217 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.671 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  15.128 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 4.545 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  22.479 ms/op
                 listUser·p0.9999: 27.783 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207242
  mean =      4.631 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 288 
    [ 2.500,  5.000) = 167751 
    [ 5.000,  7.500) = 35805 
    [ 7.500, 10.000) = 2831 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     26.662 ms/op
     p(99.9990) =     28.239 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.512 ± 2.827  ops/ms
ClientGrpc.existUser                       thrpt       3   9.216 ± 1.799  ops/ms
ClientGrpc.getUser                         thrpt       3   8.668 ± 0.419  ops/ms
ClientGrpc.listUser                        thrpt       3   6.839 ± 0.382  ops/ms
ClientGrpc.createUser                       avgt       3   3.589 ± 0.445   ms/op
ClientGrpc.existUser                        avgt       3   3.495 ± 0.223   ms/op
ClientGrpc.getUser                          avgt       3   3.702 ± 1.671   ms/op
ClientGrpc.listUser                         avgt       3   4.614 ± 1.950   ms/op
ClientGrpc.createUser                     sample  261179   3.674 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.926           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.401           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.177           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.310           ms/op
ClientGrpc.existUser                      sample  272898   3.515 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.771           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.339           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.904           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.473           ms/op
ClientGrpc.getUser                        sample  262219   3.662 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.321           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.216           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  207242   4.631 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.217           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.473           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.398           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.954           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.728           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.662           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.688           ms/op
