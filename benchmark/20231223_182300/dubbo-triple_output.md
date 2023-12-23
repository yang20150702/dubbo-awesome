# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.164 ops/ms
# Warmup Iteration   2: 12.141 ops/ms
# Warmup Iteration   3: 12.292 ops/ms
Iteration   1: 12.564 ops/ms
Iteration   2: 12.544 ops/ms
Iteration   3: 12.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.582 ±(99.9%) 0.910 ops/ms [Average]
  (min, avg, max) = (12.544, 12.582, 12.639), stdev = 0.050
  CI (99.9%): [11.673, 13.492] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.225 ops/ms
# Warmup Iteration   2: 13.090 ops/ms
# Warmup Iteration   3: 13.108 ops/ms
Iteration   1: 13.108 ops/ms
Iteration   2: 13.278 ops/ms
Iteration   3: 13.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.192 ±(99.9%) 1.557 ops/ms [Average]
  (min, avg, max) = (13.108, 13.192, 13.278), stdev = 0.085
  CI (99.9%): [11.635, 14.749] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.788 ops/ms
# Warmup Iteration   2: 12.359 ops/ms
# Warmup Iteration   3: 12.779 ops/ms
Iteration   1: 12.844 ops/ms
Iteration   2: 12.926 ops/ms
Iteration   3: 12.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.885 ±(99.9%) 0.747 ops/ms [Average]
  (min, avg, max) = (12.844, 12.885, 12.926), stdev = 0.041
  CI (99.9%): [12.137, 13.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.935 ops/ms
# Warmup Iteration   2: 10.591 ops/ms
# Warmup Iteration   3: 10.789 ops/ms
Iteration   1: 10.874 ops/ms
Iteration   2: 10.851 ops/ms
Iteration   3: 10.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.829 ±(99.9%) 1.061 ops/ms [Average]
  (min, avg, max) = (10.764, 10.829, 10.874), stdev = 0.058
  CI (99.9%): [9.769, 11.890] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.511, 2.518, 2.530), stdev = 0.010
  CI (99.9%): [2.331, 2.705] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.460, 2.467, 2.477), stdev = 0.009
  CI (99.9%): [2.305, 2.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
Iteration   3: 2.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (2.495, 2.499, 2.503), stdev = 0.004
  CI (99.9%): [2.426, 2.573] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.628 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 3.011 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.998 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.989, 2.998, 3.011), stdev = 0.012
  CI (99.9%): [2.782, 3.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
Iteration   1: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  11.808 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  10.156 ms/op
                 createUser·p0.9999: 14.931 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  8.974 ms/op
                 createUser·p0.9999: 11.436 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378682
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 182029 
    [ 2.500,  3.750) = 192849 
    [ 3.750,  5.000) = 3029 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      9.311 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     15.044 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.672 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.692 ms/op
                 existUser·p0.9999: 14.502 ms/op
                 existUser·p1.00:   16.122 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.334 ms/op
                 existUser·p0.999:  7.592 ms/op
                 existUser·p0.9999: 12.714 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  8.567 ms/op
                 existUser·p0.9999: 12.583 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386743
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 189540 
    [ 2.500,  3.750) = 194429 
    [ 3.750,  5.000) = 1924 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =      8.387 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     15.536 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.931 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  8.145 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  8.103 ms/op
                 getUser·p0.9999: 12.214 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  8.254 ms/op
                 getUser·p0.9999: 10.645 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385349
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 191299 
    [ 2.500,  3.750) = 190641 
    [ 3.750,  5.000) = 2719 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      6.777 ms/op
     p(99.9900) =     13.007 ms/op
     p(99.9990) =     14.240 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.678 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.670 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  8.990 ms/op
                 listUser·p0.9999: 10.328 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   2: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.661 ms/op
                 listUser·p0.9999: 11.340 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.243 ms/op
                 listUser·p0.9999: 10.906 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322439
  mean =      2.975 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 104075 
    [ 2.500,  3.750) = 181062 
    [ 3.750,  5.000) = 29448 
    [ 5.000,  6.250) = 6314 
    [ 6.250,  7.500) = 726 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 315 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     10.986 ms/op
     p(99.9990) =     11.929 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.582 ± 0.910  ops/ms
ClientPb.existUser                       thrpt       3  13.192 ± 1.557  ops/ms
ClientPb.getUser                         thrpt       3  12.885 ± 0.747  ops/ms
ClientPb.listUser                        thrpt       3  10.829 ± 1.061  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.187   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.162   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.073   ms/op
ClientPb.listUser                         avgt       3   2.998 ± 0.216   ms/op
ClientPb.createUser                     sample  378682   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.311           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.696           ms/op
ClientPb.existUser                      sample  386743   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.653           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.387           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.122           ms/op
ClientPb.getUser                        sample  385349   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.792           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.777           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.007           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  322439   2.975 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.670           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.986           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.059           ms/op
