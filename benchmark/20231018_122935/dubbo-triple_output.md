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
# Warmup Iteration   1: 1.008 ops/ms
# Warmup Iteration   2: 2.257 ops/ms
# Warmup Iteration   3: 4.672 ops/ms
Iteration   1: 5.141 ops/ms
Iteration   2: 5.205 ops/ms
Iteration   3: 5.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.270 ±(99.9%) 3.121 ops/ms [Average]
  (min, avg, max) = (5.141, 5.270, 5.464), stdev = 0.171
  CI (99.9%): [2.149, 8.391] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.586 ops/ms
# Warmup Iteration   2: 4.407 ops/ms
# Warmup Iteration   3: 5.816 ops/ms
Iteration   1: 5.961 ops/ms
Iteration   2: 6.028 ops/ms
Iteration   3: 6.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.037 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (5.961, 6.037, 6.124), stdev = 0.082
  CI (99.9%): [4.543, 7.532] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.615 ops/ms
# Warmup Iteration   2: 4.178 ops/ms
# Warmup Iteration   3: 5.726 ops/ms
Iteration   1: 5.684 ops/ms
Iteration   2: 5.558 ops/ms
Iteration   3: 5.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.648 ±(99.9%) 1.436 ops/ms [Average]
  (min, avg, max) = (5.558, 5.648, 5.703), stdev = 0.079
  CI (99.9%): [4.211, 7.084] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.576 ops/ms
# Warmup Iteration   2: 3.703 ops/ms
# Warmup Iteration   3: 4.767 ops/ms
Iteration   1: 4.747 ops/ms
Iteration   2: 4.914 ops/ms
Iteration   3: 4.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.814 ±(99.9%) 1.607 ops/ms [Average]
  (min, avg, max) = (4.747, 4.814, 4.914), stdev = 0.088
  CI (99.9%): [3.207, 6.422] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 20.661 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.983 ±(99.9%) 0.009 ms/op
Iteration   1: 5.863 ±(99.9%) 0.010 ms/op
Iteration   2: 5.564 ±(99.9%) 0.011 ms/op
Iteration   3: 5.581 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.669 ±(99.9%) 3.059 ms/op [Average]
  (min, avg, max) = (5.564, 5.669, 5.863), stdev = 0.168
  CI (99.9%): [2.610, 8.728] (assumes normal distribution)


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
# Warmup Iteration   1: 18.089 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.971 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.000 ±(99.9%) 0.012 ms/op
Iteration   1: 5.788 ±(99.9%) 0.014 ms/op
Iteration   2: 5.769 ±(99.9%) 0.008 ms/op
Iteration   3: 5.743 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.767 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (5.743, 5.767, 5.788), stdev = 0.022
  CI (99.9%): [5.359, 6.175] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.297 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.598 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.970 ±(99.9%) 0.012 ms/op
Iteration   1: 5.860 ±(99.9%) 0.014 ms/op
Iteration   2: 5.637 ±(99.9%) 0.011 ms/op
Iteration   3: 5.766 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.754 ±(99.9%) 2.047 ms/op [Average]
  (min, avg, max) = (5.637, 5.754, 5.860), stdev = 0.112
  CI (99.9%): [3.707, 7.801] (assumes normal distribution)


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
# Warmup Iteration   1: 20.214 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 10.220 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 7.071 ±(99.9%) 0.009 ms/op
Iteration   1: 6.794 ±(99.9%) 0.010 ms/op
Iteration   2: 6.518 ±(99.9%) 0.012 ms/op
Iteration   3: 6.696 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.669 ±(99.9%) 2.548 ms/op [Average]
  (min, avg, max) = (6.518, 6.669, 6.794), stdev = 0.140
  CI (99.9%): [4.121, 9.217] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.393 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 7.339 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.214 ±(99.9%) 0.028 ms/op
Iteration   1: 5.733 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.052 ms/op
                 createUser·p0.50:   5.415 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   8.053 ms/op
                 createUser·p0.99:   11.585 ms/op
                 createUser·p0.999:  29.682 ms/op
                 createUser·p0.9999: 37.731 ms/op
                 createUser·p1.00:   38.863 ms/op

Iteration   2: 5.725 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  19.268 ms/op
                 createUser·p0.9999: 26.457 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   3: 5.863 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.146 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.225 ms/op
                 createUser·p0.95:   8.184 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  27.500 ms/op
                 createUser·p0.9999: 31.785 ms/op
                 createUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166265
  mean =      5.773 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 42997 
    [ 5.000,  7.500) = 111525 
    [ 7.500, 10.000) = 9161 
    [10.000, 12.500) = 1642 
    [12.500, 15.000) = 534 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.052 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     24.058 ms/op
     p(99.9900) =     34.496 ms/op
     p(99.9990) =     38.689 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.016 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 7.662 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 5.686 ±(99.9%) 0.022 ms/op
Iteration   1: 5.422 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.903 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.627 ms/op
                 existUser·p0.95:   7.823 ms/op
                 existUser·p0.99:   10.732 ms/op
                 existUser·p0.999:  16.400 ms/op
                 existUser·p0.9999: 30.553 ms/op
                 existUser·p1.00:   31.818 ms/op

Iteration   2: 5.372 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.586 ms/op
                 existUser·p0.99:   10.027 ms/op
                 existUser·p0.999:  25.521 ms/op
                 existUser·p0.9999: 32.672 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 5.544 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   6.775 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   11.223 ms/op
                 existUser·p0.999:  28.616 ms/op
                 existUser·p0.9999: 32.218 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176256
  mean =      5.445 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 73070 
    [ 5.000,  7.500) = 93191 
    [ 7.500, 10.000) = 7632 
    [10.000, 12.500) = 1439 
    [12.500, 15.000) = 578 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     32.223 ms/op
     p(99.9990) =     33.542 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 19.190 ±(99.9%) 0.304 ms/op
# Warmup Iteration   2: 7.296 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.226 ±(99.9%) 0.028 ms/op
Iteration   1: 5.897 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.236 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.660 ms/op
                 getUser·p0.95:   9.191 ms/op
                 getUser·p0.99:   12.940 ms/op
                 getUser·p0.999:  17.130 ms/op
                 getUser·p0.9999: 27.771 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   2: 5.770 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.471 ms/op
                 getUser·p0.95:   9.280 ms/op
                 getUser·p0.99:   13.468 ms/op
                 getUser·p0.999:  27.419 ms/op
                 getUser·p0.9999: 33.912 ms/op
                 getUser·p1.00:   34.341 ms/op

Iteration   3: 5.765 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   7.070 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   11.977 ms/op
                 getUser·p0.999:  29.016 ms/op
                 getUser·p0.9999: 31.960 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165145
  mean =      5.810 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 46192 
    [ 5.000,  7.500) = 103672 
    [ 7.500, 10.000) = 10233 
    [10.000, 12.500) = 3162 
    [12.500, 15.000) = 1135 
    [15.000, 17.500) = 504 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      7.348 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     12.780 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     32.408 ms/op
     p(99.9990) =     34.298 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 21.853 ±(99.9%) 0.374 ms/op
# Warmup Iteration   2: 9.034 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 7.394 ±(99.9%) 0.038 ms/op
Iteration   1: 7.063 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.015 ms/op
                 listUser·p0.50:   6.504 ms/op
                 listUser·p0.90:   9.306 ms/op
                 listUser·p0.95:   10.912 ms/op
                 listUser·p0.99:   14.912 ms/op
                 listUser·p0.999:  28.349 ms/op
                 listUser·p0.9999: 34.958 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   2: 6.944 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   13.566 ms/op
                 listUser·p0.999:  32.798 ms/op
                 listUser·p0.9999: 37.695 ms/op
                 listUser·p1.00:   41.157 ms/op

Iteration   3: 6.921 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.707 ms/op
                 listUser·p0.50:   6.595 ms/op
                 listUser·p0.90:   8.380 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   12.495 ms/op
                 listUser·p0.999:  29.852 ms/op
                 listUser·p0.9999: 36.195 ms/op
                 listUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137563
  mean =      6.976 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2109 
    [ 5.000, 10.000) = 128120 
    [10.000, 15.000) = 6443 
    [15.000, 20.000) = 568 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 134 
    [30.000, 35.000) = 119 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.015 ms/op
     p(50.0000) =      6.554 ms/op
     p(90.0000) =      8.634 ms/op
     p(95.0000) =     10.142 ms/op
     p(99.0000) =     13.779 ms/op
     p(99.9000) =     30.343 ms/op
     p(99.9900) =     36.438 ms/op
     p(99.9990) =     41.157 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.270 ± 3.121  ops/ms
ClientPb.existUser                       thrpt       3   6.037 ± 1.495  ops/ms
ClientPb.getUser                         thrpt       3   5.648 ± 1.436  ops/ms
ClientPb.listUser                        thrpt       3   4.814 ± 1.607  ops/ms
ClientPb.createUser                       avgt       3   5.669 ± 3.059   ms/op
ClientPb.existUser                        avgt       3   5.767 ± 0.408   ms/op
ClientPb.getUser                          avgt       3   5.754 ± 2.047   ms/op
ClientPb.listUser                         avgt       3   6.669 ± 2.548   ms/op
ClientPb.createUser                     sample  166265   5.773 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.052           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.995           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.977           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.058           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.496           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  176256   5.445 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.037           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.725           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.633           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.350           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.223           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  165145   5.810 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.348           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.782           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.780           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.923           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.408           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.341           ms/op
ClientPb.listUser                       sample  137563   6.976 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.015           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.554           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.634           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.142           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.779           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.343           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.438           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.157           ms/op
