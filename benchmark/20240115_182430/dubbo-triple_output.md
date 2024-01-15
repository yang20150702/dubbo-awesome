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
# Warmup Iteration   1: 5.040 ops/ms
# Warmup Iteration   2: 11.932 ops/ms
# Warmup Iteration   3: 12.218 ops/ms
Iteration   1: 12.390 ops/ms
Iteration   2: 12.433 ops/ms
Iteration   3: 12.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.414 ±(99.9%) 0.398 ops/ms [Average]
  (min, avg, max) = (12.390, 12.414, 12.433), stdev = 0.022
  CI (99.9%): [12.016, 12.813] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.490 ops/ms
# Warmup Iteration   2: 13.117 ops/ms
# Warmup Iteration   3: 13.112 ops/ms
Iteration   1: 13.148 ops/ms
Iteration   2: 13.055 ops/ms
Iteration   3: 13.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.086 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (13.055, 13.086, 13.148), stdev = 0.053
  CI (99.9%): [12.117, 14.056] (assumes normal distribution)


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
# Warmup Iteration   1: 7.719 ops/ms
# Warmup Iteration   2: 12.470 ops/ms
# Warmup Iteration   3: 12.740 ops/ms
Iteration   1: 12.883 ops/ms
Iteration   2: 12.830 ops/ms
Iteration   3: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.870 ±(99.9%) 0.652 ops/ms [Average]
  (min, avg, max) = (12.830, 12.870, 12.897), stdev = 0.036
  CI (99.9%): [12.218, 13.522] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.015 ops/ms
# Warmup Iteration   2: 10.667 ops/ms
# Warmup Iteration   3: 10.760 ops/ms
Iteration   1: 10.831 ops/ms
Iteration   2: 10.719 ops/ms
Iteration   3: 10.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.801 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (10.719, 10.801, 10.852), stdev = 0.072
  CI (99.9%): [9.493, 12.108] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.544 ±(99.9%) 0.004 ms/op
Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.544, 2.549, 2.555), stdev = 0.006
  CI (99.9%): [2.448, 2.650] (assumes normal distribution)


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.003 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.466 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.455, 2.466, 2.475), stdev = 0.010
  CI (99.9%): [2.280, 2.652] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.477, 2.485, 2.490), stdev = 0.007
  CI (99.9%): [2.354, 2.617] (assumes normal distribution)


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
# Warmup Iteration   1: 5.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.007 ms/op
Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
Iteration   3: 3.026 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.002, 3.015, 3.026), stdev = 0.012
  CI (99.9%): [2.792, 3.238] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  11.636 ms/op
                 createUser·p0.9999: 14.821 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.047 ms/op
                 createUser·p0.9999: 13.377 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.015 ms/op
                 createUser·p0.9999: 12.997 ms/op
                 createUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378941
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 183637 
    [ 2.500,  3.750) = 191573 
    [ 3.750,  5.000) = 2942 
    [ 5.000,  6.250) = 328 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.222 ms/op
     p(99.9900) =     13.633 ms/op
     p(99.9990) =     15.189 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 3.681 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  4.954 ms/op
                 existUser·p0.9999: 13.272 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  8.717 ms/op
                 existUser·p0.9999: 13.012 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  7.655 ms/op
                 existUser·p0.9999: 11.977 ms/op
                 existUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385947
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 191087 
    [ 2.500,  3.750) = 191473 
    [ 3.750,  5.000) = 2534 
    [ 5.000,  6.250) = 394 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.607 ms/op
     p(99.9900) =     12.917 ms/op
     p(99.9990) =     13.650 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  11.645 ms/op
                 getUser·p0.9999: 14.326 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  5.214 ms/op
                 getUser·p0.9999: 13.053 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  7.604 ms/op
                 getUser·p0.9999: 12.313 ms/op
                 getUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380272
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 186353 
    [ 2.500,  3.750) = 188849 
    [ 3.750,  5.000) = 4202 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      6.224 ms/op
     p(99.9900) =     13.483 ms/op
     p(99.9990) =     14.483 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
Iteration   1: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.997 ms/op
                 listUser·p0.9999: 10.355 ms/op
                 listUser·p1.00:   10.797 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.461 ms/op
                 listUser·p0.9999: 12.125 ms/op
                 listUser·p1.00:   13.025 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 10.720 ms/op
                 listUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320581
  mean =      2.992 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 96422 
    [ 2.500,  3.750) = 186517 
    [ 3.750,  5.000) = 30650 
    [ 5.000,  6.250) = 5492 
    [ 6.250,  7.500) = 695 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     11.494 ms/op
     p(99.9990) =     13.019 ms/op
     p(99.9999) =     13.025 ms/op
    p(100.0000) =     13.025 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.414 ± 0.398  ops/ms
ClientPb.existUser                       thrpt       3  13.086 ± 0.970  ops/ms
ClientPb.getUser                         thrpt       3  12.870 ± 0.652  ops/ms
ClientPb.listUser                        thrpt       3  10.801 ± 1.307  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.101   ms/op
ClientPb.existUser                        avgt       3   2.466 ± 0.186   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.132   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.223   ms/op
ClientPb.createUser                     sample  378941   2.531 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.570           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.222           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.633           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.286           ms/op
ClientPb.existUser                      sample  385947   2.485 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.846           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.607           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.917           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.713           ms/op
ClientPb.getUser                        sample  380272   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.741           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.224           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.483           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  320581   2.992 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.801           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.494           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.025           ms/op
