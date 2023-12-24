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
# Warmup Iteration   1: 4.536 ops/ms
# Warmup Iteration   2: 11.718 ops/ms
# Warmup Iteration   3: 12.379 ops/ms
Iteration   1: 12.287 ops/ms
Iteration   2: 12.651 ops/ms
Iteration   3: 13.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.660 ±(99.9%) 6.876 ops/ms [Average]
  (min, avg, max) = (12.287, 12.660, 13.041), stdev = 0.377
  CI (99.9%): [5.784, 19.535] (assumes normal distribution)


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
# Warmup Iteration   1: 7.893 ops/ms
# Warmup Iteration   2: 12.726 ops/ms
# Warmup Iteration   3: 13.113 ops/ms
Iteration   1: 13.006 ops/ms
Iteration   2: 13.159 ops/ms
Iteration   3: 13.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.088 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (13.006, 13.088, 13.159), stdev = 0.077
  CI (99.9%): [11.681, 14.495] (assumes normal distribution)


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
# Warmup Iteration   1: 8.159 ops/ms
# Warmup Iteration   2: 12.210 ops/ms
# Warmup Iteration   3: 12.471 ops/ms
Iteration   1: 12.699 ops/ms
Iteration   2: 12.525 ops/ms
Iteration   3: 12.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.626 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (12.525, 12.626, 12.699), stdev = 0.090
  CI (99.9%): [10.981, 14.271] (assumes normal distribution)


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
# Warmup Iteration   1: 6.329 ops/ms
# Warmup Iteration   2: 10.529 ops/ms
# Warmup Iteration   3: 10.670 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.719 ops/ms
Iteration   3: 10.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.732 ±(99.9%) 0.836 ops/ms [Average]
  (min, avg, max) = (10.694, 10.732, 10.783), stdev = 0.046
  CI (99.9%): [9.896, 11.568] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
Iteration   1: 2.537 ±(99.9%) 0.005 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.521, 2.533, 2.540), stdev = 0.010
  CI (99.9%): [2.350, 2.715] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.411 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.004 ms/op
Iteration   1: 2.418 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (2.418, 2.445, 2.464), stdev = 0.024
  CI (99.9%): [1.998, 2.892] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.486, 2.496, 2.510), stdev = 0.013
  CI (99.9%): [2.261, 2.730] (assumes normal distribution)


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.004 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
Iteration   3: 3.019 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.008, 3.019, 3.029), stdev = 0.010
  CI (99.9%): [2.830, 3.208] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.699 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.258 ms/op
                 createUser·p0.9999: 14.354 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  9.707 ms/op
                 createUser·p0.9999: 12.148 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 10.912 ms/op
                 createUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376906
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 180865 
    [ 2.500,  3.750) = 191484 
    [ 3.750,  5.000) = 3724 
    [ 5.000,  6.250) = 331 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      9.610 ms/op
     p(99.9900) =     13.778 ms/op
     p(99.9990) =     14.632 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.638 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  8.813 ms/op
                 existUser·p0.9999: 15.039 ms/op
                 existUser·p1.00:   15.827 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  6.365 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   13.894 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  7.834 ms/op
                 existUser·p0.9999: 11.440 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390148
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 191933 
    [ 2.500,  3.750) = 194189 
    [ 3.750,  5.000) = 2990 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      7.127 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     15.665 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 13.847 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  6.175 ms/op
                 getUser·p0.9999: 12.296 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  8.691 ms/op
                 getUser·p0.9999: 11.833 ms/op
                 getUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380636
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 185953 
    [ 2.500,  3.750) = 188613 
    [ 3.750,  5.000) = 4592 
    [ 5.000,  6.250) = 968 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      6.712 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 4.968 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.960 ms/op
                 listUser·p0.9999: 11.296 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.497 ms/op
                 listUser·p0.9999: 11.844 ms/op
                 listUser·p1.00:   13.500 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.850 ms/op
                 listUser·p0.9999: 10.929 ms/op
                 listUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318893
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 92499 
    [ 2.500,  3.750) = 186830 
    [ 3.750,  5.000) = 32304 
    [ 5.000,  6.250) = 5866 
    [ 6.250,  7.500) = 649 
    [ 7.500,  8.750) = 236 
    [ 8.750, 10.000) = 238 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     11.389 ms/op
     p(99.9990) =     13.321 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.660 ± 6.876  ops/ms
ClientPb.existUser                       thrpt       3  13.088 ± 1.407  ops/ms
ClientPb.getUser                         thrpt       3  12.626 ± 1.645  ops/ms
ClientPb.listUser                        thrpt       3  10.732 ± 0.836  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.183   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.447   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.234   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.189   ms/op
ClientPb.createUser                     sample  376906   2.545 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.802           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.610           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.778           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  390148   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.555           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.127           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.680           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.827           ms/op
ClientPb.getUser                        sample  380636   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.530           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.712           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.238           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.976           ms/op
ClientPb.listUser                       sample  318893   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.907           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.500           ms/op
