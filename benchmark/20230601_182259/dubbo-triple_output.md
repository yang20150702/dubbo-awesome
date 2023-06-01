# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.879 ops/ms
# Warmup Iteration   2: 4.243 ops/ms
# Warmup Iteration   3: 7.616 ops/ms
Iteration   1: 7.449 ops/ms
Iteration   2: 7.895 ops/ms
Iteration   3: 8.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.816 ±(99.9%) 6.092 ops/ms [Average]
  (min, avg, max) = (7.449, 7.816, 8.103), stdev = 0.334
  CI (99.9%): [1.724, 13.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.383 ops/ms
# Warmup Iteration   2: 6.918 ops/ms
# Warmup Iteration   3: 7.786 ops/ms
Iteration   1: 8.251 ops/ms
Iteration   2: 8.008 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.061 ±(99.9%) 3.087 ops/ms [Average]
  (min, avg, max) = (7.925, 8.061, 8.251), stdev = 0.169
  CI (99.9%): [4.974, 11.149] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 6.488 ops/ms
# Warmup Iteration   3: 7.758 ops/ms
Iteration   1: 7.728 ops/ms
Iteration   2: 7.767 ops/ms
Iteration   3: 7.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.809 ±(99.9%) 1.960 ops/ms [Average]
  (min, avg, max) = (7.728, 7.809, 7.931), stdev = 0.107
  CI (99.9%): [5.849, 9.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.145 ops/ms
# Warmup Iteration   2: 5.817 ops/ms
# Warmup Iteration   3: 6.641 ops/ms
Iteration   1: 6.770 ops/ms
Iteration   2: 6.869 ops/ms
Iteration   3: 7.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.927 ±(99.9%) 3.523 ops/ms [Average]
  (min, avg, max) = (6.770, 6.927, 7.143), stdev = 0.193
  CI (99.9%): [3.404, 10.450] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.173 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.010 ms/op
Iteration   1: 4.222 ±(99.9%) 0.010 ms/op
Iteration   2: 3.995 ±(99.9%) 0.007 ms/op
Iteration   3: 3.950 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.056 ±(99.9%) 2.665 ms/op [Average]
  (min, avg, max) = (3.950, 4.056, 4.222), stdev = 0.146
  CI (99.9%): [1.391, 6.721] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.748 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.005 ms/op
Iteration   1: 3.801 ±(99.9%) 0.008 ms/op
Iteration   2: 3.811 ±(99.9%) 0.006 ms/op
Iteration   3: 3.887 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.833 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.801, 3.833, 3.887), stdev = 0.047
  CI (99.9%): [2.980, 4.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.068 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.019 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.007 ms/op
Iteration   1: 4.162 ±(99.9%) 0.010 ms/op
Iteration   2: 4.138 ±(99.9%) 0.009 ms/op
Iteration   3: 4.166 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.155 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (4.138, 4.155, 4.166), stdev = 0.015
  CI (99.9%): [3.879, 4.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.065 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.467 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.878 ±(99.9%) 0.010 ms/op
Iteration   1: 4.767 ±(99.9%) 0.010 ms/op
Iteration   2: 4.770 ±(99.9%) 0.011 ms/op
Iteration   3: 4.725 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.754 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (4.725, 4.754, 4.770), stdev = 0.025
  CI (99.9%): [4.303, 5.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.158 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.940 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.017 ms/op
Iteration   1: 4.020 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.985 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.082 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 4.231 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.025 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   8.102 ms/op
                 createUser·p0.999:  14.184 ms/op
                 createUser·p0.9999: 29.815 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   3: 4.101 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.685 ms/op
                 createUser·p0.99:   7.028 ms/op
                 createUser·p0.999:  29.195 ms/op
                 createUser·p0.9999: 35.678 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233118
  mean =      4.116 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 217 
    [ 2.500,  5.000) = 213888 
    [ 5.000,  7.500) = 16818 
    [ 7.500, 10.000) = 1381 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     24.146 ms/op
     p(99.9900) =     34.234 ms/op
     p(99.9990) =     36.176 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.603 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.392 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.009 ms/op
Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.553 ms/op
                 existUser·p0.999:  22.774 ms/op
                 existUser·p0.9999: 31.408 ms/op
                 existUser·p1.00:   32.604 ms/op

Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  10.500 ms/op
                 existUser·p0.9999: 31.324 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.028 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   7.541 ms/op
                 existUser·p0.999:  13.795 ms/op
                 existUser·p0.9999: 33.423 ms/op
                 existUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243160
  mean =      3.946 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 253 
    [ 2.500,  5.000) = 230687 
    [ 5.000,  7.500) = 9753 
    [ 7.500, 10.000) = 1948 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     13.787 ms/op
     p(99.9900) =     32.508 ms/op
     p(99.9990) =     36.830 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.160 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 5.078 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.442 ±(99.9%) 0.016 ms/op
Iteration   1: 4.206 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  24.640 ms/op
                 getUser·p0.9999: 34.051 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   2: 3.984 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  11.038 ms/op
                 getUser·p0.9999: 28.179 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 4.169 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.527 ms/op
                 getUser·p0.999:  26.324 ms/op
                 getUser·p0.9999: 30.922 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233031
  mean =      4.117 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 218871 
    [ 5.000,  7.500) = 11660 
    [ 7.500, 10.000) = 1685 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 132 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.676 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     24.609 ms/op
     p(99.9900) =     30.523 ms/op
     p(99.9990) =     35.172 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.154 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 6.314 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.844 ±(99.9%) 0.016 ms/op
Iteration   1: 4.949 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  25.487 ms/op
                 listUser·p0.9999: 31.609 ms/op
                 listUser·p1.00:   32.899 ms/op

Iteration   2: 4.878 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  18.887 ms/op
                 listUser·p0.9999: 23.483 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   3: 4.854 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.735 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196074
  mean =      4.893 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 144795 
    [ 5.000,  7.500) = 45083 
    [ 7.500, 10.000) = 5162 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     18.837 ms/op
     p(99.9900) =     29.832 ms/op
     p(99.9990) =     32.521 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.816 ± 6.092  ops/ms
ClientPb.existUser                       thrpt       3   8.061 ± 3.087  ops/ms
ClientPb.getUser                         thrpt       3   7.809 ± 1.960  ops/ms
ClientPb.listUser                        thrpt       3   6.927 ± 3.523  ops/ms
ClientPb.createUser                       avgt       3   4.056 ± 2.665   ms/op
ClientPb.existUser                        avgt       3   3.833 ± 0.853   ms/op
ClientPb.getUser                          avgt       3   4.155 ± 0.277   ms/op
ClientPb.listUser                         avgt       3   4.754 ± 0.451   ms/op
ClientPb.createUser                     sample  233118   4.116 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.649           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.324           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.146           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.234           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.241           ms/op
ClientPb.existUser                      sample  243160   3.946 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.264           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.520           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.787           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.508           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.290           ms/op
ClientPb.getUser                        sample  233031   4.117 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.655           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.676           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.561           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.609           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.523           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  196074   4.893 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.735           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.995           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.837           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.832           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.899           ms/op
