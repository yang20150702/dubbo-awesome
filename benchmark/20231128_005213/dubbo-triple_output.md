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
# Warmup Iteration   1: 5.125 ops/ms
# Warmup Iteration   2: 12.109 ops/ms
# Warmup Iteration   3: 12.406 ops/ms
Iteration   1: 12.671 ops/ms
Iteration   2: 12.735 ops/ms
Iteration   3: 12.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.747 ±(99.9%) 1.511 ops/ms [Average]
  (min, avg, max) = (12.671, 12.747, 12.836), stdev = 0.083
  CI (99.9%): [11.236, 14.258] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ops/ms
# Warmup Iteration   2: 13.085 ops/ms
# Warmup Iteration   3: 13.112 ops/ms
Iteration   1: 13.169 ops/ms
Iteration   2: 13.069 ops/ms
Iteration   3: 13.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.094 ±(99.9%) 1.196 ops/ms [Average]
  (min, avg, max) = (13.045, 13.094, 13.169), stdev = 0.066
  CI (99.9%): [11.898, 14.291] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.440 ops/ms
# Warmup Iteration   2: 12.703 ops/ms
# Warmup Iteration   3: 12.832 ops/ms
Iteration   1: 12.912 ops/ms
Iteration   2: 12.923 ops/ms
Iteration   3: 12.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.833 ±(99.9%) 2.671 ops/ms [Average]
  (min, avg, max) = (12.664, 12.833, 12.923), stdev = 0.146
  CI (99.9%): [10.161, 15.504] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.868 ops/ms
# Warmup Iteration   2: 10.614 ops/ms
# Warmup Iteration   3: 10.760 ops/ms
Iteration   1: 10.696 ops/ms
Iteration   2: 10.729 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.731 ±(99.9%) 0.646 ops/ms [Average]
  (min, avg, max) = (10.696, 10.731, 10.767), stdev = 0.035
  CI (99.9%): [10.085, 11.377] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.005 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.503 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.486, 2.503, 2.526), stdev = 0.020
  CI (99.9%): [2.132, 2.873] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.466 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (2.446, 2.466, 2.479), stdev = 0.018
  CI (99.9%): [2.147, 2.786] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.896 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.496, 2.504, 2.517), stdev = 0.012
  CI (99.9%): [2.289, 2.718] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.004 ms/op
Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
Iteration   3: 2.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.993, 2.997, 3.000), stdev = 0.004
  CI (99.9%): [2.923, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  7.342 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 12.211 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  7.766 ms/op
                 createUser·p0.9999: 9.328 ms/op
                 createUser·p1.00:   10.027 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383691
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 185679 
    [ 2.500,  3.750) = 193966 
    [ 3.750,  5.000) = 3075 
    [ 5.000,  6.250) = 450 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      7.738 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.082 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  5.808 ms/op
                 existUser·p0.9999: 14.053 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.548 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  5.867 ms/op
                 existUser·p0.9999: 11.719 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  9.009 ms/op
                 existUser·p0.9999: 12.239 ms/op
                 existUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387810
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 193280 
    [ 2.500,  3.750) = 190934 
    [ 3.750,  5.000) = 2839 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      7.140 ms/op
     p(99.9900) =     13.520 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  10.650 ms/op
                 getUser·p0.9999: 13.591 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  9.585 ms/op
                 getUser·p0.9999: 12.195 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  8.188 ms/op
                 getUser·p0.9999: 11.325 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382453
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 189286 
    [ 2.500,  3.750) = 187429 
    [ 3.750,  5.000) = 4065 
    [ 5.000,  6.250) = 1060 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      8.295 ms/op
     p(99.9900) =     13.177 ms/op
     p(99.9990) =     13.831 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.009 ms/op
Iteration   1: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.857 ms/op
                 listUser·p0.9999: 11.502 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.740 ms/op
                 listUser·p0.9999: 11.461 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.744 ms/op
                 listUser·p0.9999: 19.408 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322174
  mean =      2.977 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 98660 
    [ 2.500,  3.750) = 186174 
    [ 3.750,  5.000) = 29935 
    [ 5.000,  6.250) = 5938 
    [ 6.250,  7.500) = 607 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 199 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     14.479 ms/op
     p(99.9990) =     19.588 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.747 ± 1.511  ops/ms
ClientPb.existUser                       thrpt       3  13.094 ± 1.196  ops/ms
ClientPb.getUser                         thrpt       3  12.833 ± 2.671  ops/ms
ClientPb.listUser                        thrpt       3  10.731 ± 0.646  ops/ms
ClientPb.createUser                       avgt       3   2.503 ± 0.371   ms/op
ClientPb.existUser                        avgt       3   2.466 ± 0.320   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.214   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.074   ms/op
ClientPb.createUser                     sample  383691   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.428           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.738           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  387810   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.548           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.140           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.520           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  382453   2.508 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.295           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.177           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.022           ms/op
ClientPb.listUser                       sample  322174   2.977 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.765           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.479           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.956           ms/op
