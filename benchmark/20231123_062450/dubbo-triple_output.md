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
# Warmup Iteration   1: 4.844 ops/ms
# Warmup Iteration   2: 12.203 ops/ms
# Warmup Iteration   3: 12.397 ops/ms
Iteration   1: 12.540 ops/ms
Iteration   2: 12.635 ops/ms
Iteration   3: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.654 ±(99.9%) 2.291 ops/ms [Average]
  (min, avg, max) = (12.540, 12.654, 12.789), stdev = 0.126
  CI (99.9%): [10.364, 14.945] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.891 ops/ms
# Warmup Iteration   2: 12.632 ops/ms
# Warmup Iteration   3: 12.664 ops/ms
Iteration   1: 12.832 ops/ms
Iteration   2: 12.772 ops/ms
Iteration   3: 12.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.801 ±(99.9%) 0.545 ops/ms [Average]
  (min, avg, max) = (12.772, 12.801, 12.832), stdev = 0.030
  CI (99.9%): [12.256, 13.345] (assumes normal distribution)


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
# Warmup Iteration   1: 7.019 ops/ms
# Warmup Iteration   2: 12.403 ops/ms
# Warmup Iteration   3: 12.530 ops/ms
Iteration   1: 12.713 ops/ms
Iteration   2: 12.729 ops/ms
Iteration   3: 12.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.689 ±(99.9%) 1.022 ops/ms [Average]
  (min, avg, max) = (12.625, 12.689, 12.729), stdev = 0.056
  CI (99.9%): [11.666, 13.711] (assumes normal distribution)


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
# Warmup Iteration   1: 6.583 ops/ms
# Warmup Iteration   2: 10.253 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.460 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.499 ±(99.9%) 1.536 ops/ms [Average]
  (min, avg, max) = (10.441, 10.499, 10.595), stdev = 0.084
  CI (99.9%): [8.962, 12.035] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.557 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (2.521, 2.545, 2.557), stdev = 0.021
  CI (99.9%): [2.163, 2.927] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.003 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.169 ms/op [Average]
  (min, avg, max) = (2.475, 2.482, 2.492), stdev = 0.009
  CI (99.9%): [2.313, 2.650] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.533 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (2.519, 2.533, 2.546), stdev = 0.014
  CI (99.9%): [2.285, 2.780] (assumes normal distribution)


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
Iteration   1: 3.099 ±(99.9%) 0.005 ms/op
Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
Iteration   3: 3.126 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.113 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (3.099, 3.113, 3.126), stdev = 0.013
  CI (99.9%): [2.872, 3.353] (assumes normal distribution)


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.706 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  11.447 ms/op
                 createUser·p0.9999: 14.149 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.782 ms/op
                 createUser·p0.999:  9.164 ms/op
                 createUser·p0.9999: 11.975 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  8.675 ms/op
                 createUser·p0.9999: 10.650 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375896
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 179714 
    [ 2.500,  3.750) = 191225 
    [ 3.750,  5.000) = 3981 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.015 ms/op
     p(99.9900) =     13.655 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.404 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.940 ms/op
                 existUser·p0.9999: 14.085 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  5.799 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.396 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  6.553 ms/op
                 existUser·p0.9999: 10.764 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400138
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 209096 
    [ 2.500,  3.750) = 187790 
    [ 3.750,  5.000) = 2442 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      2.425 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.331 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  11.802 ms/op
                 getUser·p0.9999: 13.817 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  10.670 ms/op
                 getUser·p0.9999: 13.003 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  8.508 ms/op
                 getUser·p0.9999: 10.714 ms/op
                 getUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378784
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 184492 
    [ 2.500,  3.750) = 188147 
    [ 3.750,  5.000) = 4802 
    [ 5.000,  6.250) = 838 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.093 ms/op
     p(99.9000) =      8.592 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.097 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 4.807 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.008 ms/op
Iteration   1: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  8.760 ms/op
                 listUser·p0.9999: 10.380 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 12.049 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 11.173 ms/op
                 listUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316046
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 91601 
    [ 2.500,  3.750) = 181745 
    [ 3.750,  5.000) = 33818 
    [ 5.000,  6.250) = 7000 
    [ 6.250,  7.500) = 1061 
    [ 7.500,  8.750) = 253 
    [ 8.750, 10.000) = 262 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =      9.338 ms/op
     p(99.9900) =     11.721 ms/op
     p(99.9990) =     12.574 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.654 ± 2.291  ops/ms
ClientPb.existUser                       thrpt       3  12.801 ± 0.545  ops/ms
ClientPb.getUser                         thrpt       3  12.689 ± 1.022  ops/ms
ClientPb.listUser                        thrpt       3  10.499 ± 1.536  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.382   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.169   ms/op
ClientPb.getUser                          avgt       3   2.533 ± 0.248   ms/op
ClientPb.listUser                         avgt       3   3.113 ± 0.241   ms/op
ClientPb.createUser                     sample  375896   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.808           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.015           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.655           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  400138   2.398 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.941           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.425           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.331           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.861           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.664           ms/op
ClientPb.getUser                        sample  378784   2.532 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.691           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.093           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.592           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.369           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.287           ms/op
ClientPb.listUser                       sample  316046   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.338           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.721           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
