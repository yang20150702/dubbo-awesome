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
# Warmup Iteration   1: 4.740 ops/ms
# Warmup Iteration   2: 12.325 ops/ms
# Warmup Iteration   3: 12.157 ops/ms
Iteration   1: 12.467 ops/ms
Iteration   2: 12.607 ops/ms
Iteration   3: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.575 ±(99.9%) 1.745 ops/ms [Average]
  (min, avg, max) = (12.467, 12.575, 12.651), stdev = 0.096
  CI (99.9%): [10.830, 14.320] (assumes normal distribution)


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
# Warmup Iteration   1: 8.134 ops/ms
# Warmup Iteration   2: 13.046 ops/ms
# Warmup Iteration   3: 13.022 ops/ms
Iteration   1: 12.980 ops/ms
Iteration   2: 13.184 ops/ms
Iteration   3: 12.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.038 ±(99.9%) 2.326 ops/ms [Average]
  (min, avg, max) = (12.949, 13.038, 13.184), stdev = 0.127
  CI (99.9%): [10.712, 15.363] (assumes normal distribution)


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
# Warmup Iteration   1: 7.728 ops/ms
# Warmup Iteration   2: 12.437 ops/ms
# Warmup Iteration   3: 12.599 ops/ms
Iteration   1: 12.477 ops/ms
Iteration   2: 12.560 ops/ms
Iteration   3: 12.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.542 ±(99.9%) 1.068 ops/ms [Average]
  (min, avg, max) = (12.477, 12.542, 12.590), stdev = 0.059
  CI (99.9%): [11.474, 13.611] (assumes normal distribution)


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
# Warmup Iteration   1: 6.800 ops/ms
# Warmup Iteration   2: 10.545 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.556 ops/ms
Iteration   2: 10.520 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.560 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (10.520, 10.560, 10.604), stdev = 0.042
  CI (99.9%): [9.791, 11.328] (assumes normal distribution)


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
Iteration   3: 2.512 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (2.512, 2.542, 2.568), stdev = 0.028
  CI (99.9%): [2.027, 3.057] (assumes normal distribution)


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
Iteration   1: 2.573 ±(99.9%) 0.005 ms/op
Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
Iteration   3: 2.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.564 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (2.552, 2.564, 2.573), stdev = 0.011
  CI (99.9%): [2.362, 2.766] (assumes normal distribution)


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.535 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.521, 2.535, 2.553), stdev = 0.016
  CI (99.9%): [2.241, 2.829] (assumes normal distribution)


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
# Warmup Iteration   1: 5.143 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
Iteration   2: 3.095 ±(99.9%) 0.005 ms/op
Iteration   3: 3.081 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.098 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.081, 3.098, 3.118), stdev = 0.019
  CI (99.9%): [2.760, 3.436] (assumes normal distribution)


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.594 ±(99.9%) 0.006 ms/op
Iteration   1: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  12.185 ms/op
                 createUser·p0.9999: 14.057 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.579 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  9.767 ms/op
                 createUser·p0.9999: 17.859 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   3: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.024 ms/op
                 createUser·p0.999:  8.850 ms/op
                 createUser·p0.9999: 10.904 ms/op
                 createUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372918
  mean =      2.572 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 177544 
    [ 2.500,  3.750) = 190319 
    [ 3.750,  5.000) = 3782 
    [ 5.000,  6.250) = 683 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     14.141 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 3.934 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  5.853 ms/op
                 existUser·p0.9999: 14.173 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  9.194 ms/op
                 existUser·p0.9999: 13.927 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 11.294 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383581
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 190046 
    [ 2.500,  3.750) = 188684 
    [ 3.750,  5.000) = 3820 
    [ 5.000,  6.250) = 572 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.625 ms/op
     p(99.9900) =     13.849 ms/op
     p(99.9990) =     14.814 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  11.848 ms/op
                 getUser·p0.9999: 14.772 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  10.514 ms/op
                 getUser·p0.9999: 16.013 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 11.524 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376901
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 182944 
    [ 2.500,  3.750) = 187558 
    [ 3.750,  5.000) = 5174 
    [ 5.000,  6.250) = 733 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      9.095 ms/op
     p(99.9900) =     15.526 ms/op
     p(99.9990) =     16.654 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 5.205 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.010 ms/op
Iteration   1: 3.116 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.675 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.882 ms/op
                 listUser·p0.999:  9.827 ms/op
                 listUser·p0.9999: 14.299 ms/op
                 listUser·p1.00:   14.533 ms/op

Iteration   2: 3.112 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  10.437 ms/op
                 listUser·p0.9999: 11.890 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.752 ms/op
                 listUser·p0.9999: 12.690 ms/op
                 listUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309174
  mean =      3.103 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 79352 
    [ 2.500,  3.750) = 183070 
    [ 3.750,  5.000) = 37852 
    [ 5.000,  6.250) = 7228 
    [ 6.250,  7.500) = 921 
    [ 7.500,  8.750) = 136 
    [ 8.750, 10.000) = 213 
    [10.000, 11.250) = 189 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     12.209 ms/op
     p(99.9990) =     14.431 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.575 ± 1.745  ops/ms
ClientPb.existUser                       thrpt       3  13.038 ± 2.326  ops/ms
ClientPb.getUser                         thrpt       3  12.542 ± 1.068  ops/ms
ClientPb.listUser                        thrpt       3  10.560 ± 0.769  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.515   ms/op
ClientPb.existUser                        avgt       3   2.564 ± 0.202   ms/op
ClientPb.getUser                          avgt       3   2.535 ± 0.294   ms/op
ClientPb.listUser                         avgt       3   3.098 ± 0.338   ms/op
ClientPb.createUser                     sample  372918   2.572 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.994           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.141           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.776           ms/op
ClientPb.existUser                      sample  383581   2.500 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.625           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.849           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.942           ms/op
ClientPb.getUser                        sample  376901   2.545 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.720           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.095           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.526           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.941           ms/op
ClientPb.listUser                       sample  309174   3.103 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.675           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.978           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.209           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.533           ms/op
