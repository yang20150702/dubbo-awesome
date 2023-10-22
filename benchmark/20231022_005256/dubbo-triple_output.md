# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.701 ops/ms
# Warmup Iteration   2: 4.002 ops/ms
# Warmup Iteration   3: 7.634 ops/ms
Iteration   1: 7.594 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 7.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.775 ±(99.9%) 2.936 ops/ms [Average]
  (min, avg, max) = (7.594, 7.775, 7.904), stdev = 0.161
  CI (99.9%): [4.839, 10.711] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.192 ops/ms
# Warmup Iteration   2: 6.882 ops/ms
# Warmup Iteration   3: 7.991 ops/ms
Iteration   1: 8.457 ops/ms
Iteration   2: 7.824 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.220 ±(99.9%) 6.301 ops/ms [Average]
  (min, avg, max) = (7.824, 8.220, 8.457), stdev = 0.345
  CI (99.9%): [1.919, 14.521] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.234 ops/ms
# Warmup Iteration   2: 6.517 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 8.048 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 8.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.083 ±(99.9%) 0.915 ops/ms [Average]
  (min, avg, max) = (8.048, 8.083, 8.141), stdev = 0.050
  CI (99.9%): [7.168, 8.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 5.613 ops/ms
# Warmup Iteration   3: 6.571 ops/ms
Iteration   1: 6.696 ops/ms
Iteration   2: 6.853 ops/ms
Iteration   3: 6.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.748 ±(99.9%) 1.657 ops/ms [Average]
  (min, avg, max) = (6.696, 6.748, 6.853), stdev = 0.091
  CI (99.9%): [5.091, 8.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 14.784 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.916 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.005 ms/op
Iteration   1: 3.871 ±(99.9%) 0.006 ms/op
Iteration   2: 4.158 ±(99.9%) 0.005 ms/op
Iteration   3: 3.889 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.973 ±(99.9%) 2.936 ms/op [Average]
  (min, avg, max) = (3.871, 3.973, 4.158), stdev = 0.161
  CI (99.9%): [1.037, 6.908] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.705 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.008 ms/op
Iteration   1: 3.802 ±(99.9%) 0.005 ms/op
Iteration   2: 4.207 ±(99.9%) 0.004 ms/op
Iteration   3: 3.936 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.982 ±(99.9%) 3.762 ms/op [Average]
  (min, avg, max) = (3.802, 3.982, 4.207), stdev = 0.206
  CI (99.9%): [0.220, 7.743] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 11.101 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.360 ±(99.9%) 0.006 ms/op
Iteration   1: 3.871 ±(99.9%) 0.005 ms/op
Iteration   2: 3.847 ±(99.9%) 0.005 ms/op
Iteration   3: 3.822 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.847 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.822, 3.847, 3.871), stdev = 0.024
  CI (99.9%): [3.404, 4.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.076 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.336 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.726 ±(99.9%) 0.007 ms/op
Iteration   1: 4.736 ±(99.9%) 0.010 ms/op
Iteration   2: 4.719 ±(99.9%) 0.007 ms/op
Iteration   3: 4.517 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.657 ±(99.9%) 2.226 ms/op [Average]
  (min, avg, max) = (4.517, 4.657, 4.736), stdev = 0.122
  CI (99.9%): [2.432, 6.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.726 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 4.940 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.365 ±(99.9%) 0.017 ms/op
Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.389 ms/op
                 createUser·p0.999:  23.409 ms/op
                 createUser·p0.9999: 27.231 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   2: 3.892 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  25.586 ms/op
                 createUser·p0.9999: 28.225 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.941 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   8.152 ms/op
                 createUser·p0.999:  19.261 ms/op
                 createUser·p0.9999: 31.250 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242868
  mean =      3.950 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 671 
    [ 2.500,  5.000) = 229266 
    [ 5.000,  7.500) = 10497 
    [ 7.500, 10.000) = 1546 
    [10.000, 12.500) = 430 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     22.902 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     32.103 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.969 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.015 ms/op
Iteration   1: 3.838 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  20.615 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.786 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.920 ms/op
                 existUser·p0.999:  18.311 ms/op
                 existUser·p0.9999: 26.745 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 3.839 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.357 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  25.212 ms/op
                 existUser·p0.9999: 29.087 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251261
  mean =      3.821 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1055 
    [ 2.500,  5.000) = 241005 
    [ 5.000,  7.500) = 7256 
    [ 7.500, 10.000) = 1287 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     28.397 ms/op
     p(99.9990) =     30.261 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 12.952 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 5.013 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.016 ms/op
Iteration   1: 4.138 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.071 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  23.483 ms/op
                 getUser·p0.9999: 29.128 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   2: 4.147 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   6.136 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  16.320 ms/op
                 getUser·p0.9999: 28.322 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 3.976 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  29.004 ms/op
                 getUser·p0.9999: 31.420 ms/op
                 getUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234895
  mean =      4.085 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 199 
    [ 2.500,  5.000) = 216217 
    [ 5.000,  7.500) = 14084 
    [ 7.500, 10.000) = 3356 
    [10.000, 12.500) = 536 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     23.734 ms/op
     p(99.9900) =     30.786 ms/op
     p(99.9990) =     32.167 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.220 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.359 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.814 ±(99.9%) 0.017 ms/op
Iteration   1: 4.879 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  23.281 ms/op
                 listUser·p0.9999: 27.831 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 4.901 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  19.694 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   3: 4.742 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.740 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 27.960 ms/op
                 listUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198151
  mean =      4.840 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 151263 
    [ 5.000,  7.500) = 41301 
    [ 7.500, 10.000) = 4296 
    [10.000, 12.500) = 702 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.250 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     21.098 ms/op
     p(99.9900) =     27.248 ms/op
     p(99.9990) =     28.697 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.775 ± 2.936  ops/ms
ClientPb.existUser                       thrpt       3   8.220 ± 6.301  ops/ms
ClientPb.getUser                         thrpt       3   8.083 ± 0.915  ops/ms
ClientPb.listUser                        thrpt       3   6.748 ± 1.657  ops/ms
ClientPb.createUser                       avgt       3   3.973 ± 2.936   ms/op
ClientPb.existUser                        avgt       3   3.982 ± 3.762   ms/op
ClientPb.getUser                          avgt       3   3.847 ± 0.442   ms/op
ClientPb.listUser                         avgt       3   4.657 ± 2.226   ms/op
ClientPb.createUser                     sample  242868   3.950 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.579           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.504           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.902           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.408           ms/op
ClientPb.existUser                      sample  251261   3.821 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.357           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.397           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.802           ms/op
ClientPb.getUser                        sample  234895   4.085 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.593           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.743           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.364           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.734           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.786           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.637           ms/op
ClientPb.listUser                       sample  198151   4.840 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.175           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.250           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.044           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.098           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.248           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
