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
# Warmup Iteration   1: 4.858 ops/ms
# Warmup Iteration   2: 12.011 ops/ms
# Warmup Iteration   3: 12.382 ops/ms
Iteration   1: 12.537 ops/ms
Iteration   2: 12.630 ops/ms
Iteration   3: 12.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.628 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (12.537, 12.628, 12.715), stdev = 0.089
  CI (99.9%): [11.006, 14.249] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.884 ops/ms
# Warmup Iteration   2: 12.742 ops/ms
# Warmup Iteration   3: 12.977 ops/ms
Iteration   1: 12.829 ops/ms
Iteration   2: 12.956 ops/ms
Iteration   3: 12.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.895 ±(99.9%) 1.164 ops/ms [Average]
  (min, avg, max) = (12.829, 12.895, 12.956), stdev = 0.064
  CI (99.9%): [11.731, 14.059] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.424 ops/ms
# Warmup Iteration   2: 12.459 ops/ms
# Warmup Iteration   3: 12.774 ops/ms
Iteration   1: 12.702 ops/ms
Iteration   2: 12.702 ops/ms
Iteration   3: 12.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.698 ±(99.9%) 0.129 ops/ms [Average]
  (min, avg, max) = (12.690, 12.698, 12.702), stdev = 0.007
  CI (99.9%): [12.569, 12.827] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.912 ops/ms
# Warmup Iteration   2: 10.425 ops/ms
# Warmup Iteration   3: 10.550 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.655 ±(99.9%) 0.725 ops/ms [Average]
  (min, avg, max) = (10.615, 10.655, 10.694), stdev = 0.040
  CI (99.9%): [9.931, 11.380] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.865 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.511, 2.533, 2.551), stdev = 0.020
  CI (99.9%): [2.163, 2.902] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.440, 2.449, 2.462), stdev = 0.011
  CI (99.9%): [2.239, 2.659] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.003 ms/op
Iteration   1: 2.511 ±(99.9%) 0.003 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.517 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.511, 2.517, 2.521), stdev = 0.005
  CI (99.9%): [2.418, 2.615] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.005 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.048 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (3.043, 3.048, 3.055), stdev = 0.006
  CI (99.9%): [2.930, 3.167] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.587 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  11.911 ms/op
                 createUser·p0.9999: 13.966 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  9.224 ms/op
                 createUser·p0.9999: 14.451 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   3: 2.601 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.374 ms/op
                 createUser·p0.9999: 12.042 ms/op
                 createUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373835
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 178169 
    [ 2.500,  3.750) = 191234 
    [ 3.750,  5.000) = 3632 
    [ 5.000,  6.250) = 262 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.737 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  12.457 ms/op
                 existUser·p0.9999: 14.680 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  8.614 ms/op
                 existUser·p0.9999: 12.814 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   4.825 ms/op
                 existUser·p0.999:  7.545 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381611
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 184364 
    [ 2.500,  3.750) = 192590 
    [ 3.750,  5.000) = 2973 
    [ 5.000,  6.250) = 1171 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      7.572 ms/op
     p(99.9900) =     13.989 ms/op
     p(99.9990) =     15.416 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.035 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 14.287 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.588 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.638 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 14.505 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  8.296 ms/op
                 getUser·p0.9999: 13.316 ms/op
                 getUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374157
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 181611 
    [ 2.500,  3.750) = 186802 
    [ 3.750,  5.000) = 4230 
    [ 5.000,  6.250) = 941 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     14.198 ms/op
     p(99.9990) =     14.971 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.934 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.009 ms/op
Iteration   1: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.485 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.763 ms/op
                 listUser·p0.999:  10.075 ms/op
                 listUser·p0.9999: 11.633 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.707 ms/op
                 listUser·p0.9999: 10.554 ms/op
                 listUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314097
  mean =      3.054 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 83998 
    [ 2.500,  3.750) = 188067 
    [ 3.750,  5.000) = 34303 
    [ 5.000,  6.250) = 6138 
    [ 6.250,  7.500) = 767 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.452 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     11.811 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.628 ± 1.622  ops/ms
ClientPb.existUser                       thrpt       3  12.895 ± 1.164  ops/ms
ClientPb.getUser                         thrpt       3  12.698 ± 0.129  ops/ms
ClientPb.listUser                        thrpt       3  10.655 ± 0.725  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.370   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.210   ms/op
ClientPb.getUser                          avgt       3   2.517 ± 0.099   ms/op
ClientPb.listUser                         avgt       3   3.048 ± 0.118   ms/op
ClientPb.createUser                     sample  373835   2.565 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.011           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.339           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.959           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.450           ms/op
ClientPb.existUser                      sample  381611   2.513 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.605           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.572           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.989           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.630           ms/op
ClientPb.getUser                        sample  374157   2.564 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.728           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.471           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.198           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.204           ms/op
ClientPb.listUser                       sample  314097   3.054 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.850           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.452           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.878           ms/op
