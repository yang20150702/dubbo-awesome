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
# Warmup Iteration   1: 4.638 ops/ms
# Warmup Iteration   2: 11.527 ops/ms
# Warmup Iteration   3: 11.997 ops/ms
Iteration   1: 12.195 ops/ms
Iteration   2: 12.186 ops/ms
Iteration   3: 12.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.182 ±(99.9%) 0.286 ops/ms [Average]
  (min, avg, max) = (12.164, 12.182, 12.195), stdev = 0.016
  CI (99.9%): [11.896, 12.468] (assumes normal distribution)


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
# Warmup Iteration   1: 7.858 ops/ms
# Warmup Iteration   2: 12.658 ops/ms
# Warmup Iteration   3: 12.575 ops/ms
Iteration   1: 12.562 ops/ms
Iteration   2: 12.737 ops/ms
Iteration   3: 12.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.667 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (12.562, 12.667, 12.737), stdev = 0.092
  CI (99.9%): [10.980, 14.355] (assumes normal distribution)


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
# Warmup Iteration   1: 7.542 ops/ms
# Warmup Iteration   2: 12.239 ops/ms
# Warmup Iteration   3: 12.554 ops/ms
Iteration   1: 12.448 ops/ms
Iteration   2: 12.591 ops/ms
Iteration   3: 12.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.504 ±(99.9%) 1.390 ops/ms [Average]
  (min, avg, max) = (12.448, 12.504, 12.591), stdev = 0.076
  CI (99.9%): [11.115, 13.894] (assumes normal distribution)


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
# Warmup Iteration   1: 6.346 ops/ms
# Warmup Iteration   2: 10.181 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 10.332 ops/ms
Iteration   3: 10.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.353 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (10.332, 10.353, 10.392), stdev = 0.034
  CI (99.9%): [9.730, 10.975] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.004 ms/op
Iteration   1: 2.634 ±(99.9%) 0.005 ms/op
Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
Iteration   3: 2.608 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.607 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.579, 2.607, 2.634), stdev = 0.028
  CI (99.9%): [2.104, 3.110] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
Iteration   3: 2.503 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.504 ±(99.9%) 0.093 ms/op [Average]
  (min, avg, max) = (2.500, 2.504, 2.510), stdev = 0.005
  CI (99.9%): [2.411, 2.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.022 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.003 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.560 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.545, 2.560, 2.580), stdev = 0.018
  CI (99.9%): [2.231, 2.889] (assumes normal distribution)


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
Iteration   3: 3.062 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.054 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.042, 3.054, 3.062), stdev = 0.010
  CI (99.9%): [2.865, 3.243] (assumes normal distribution)


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.749 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.608 ±(99.9%) 0.006 ms/op
Iteration   1: 2.614 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 14.418 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   2: 2.607 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  9.620 ms/op
                 createUser·p0.9999: 16.511 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 2.610 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   3.868 ms/op
                 createUser·p0.999:  8.987 ms/op
                 createUser·p0.9999: 11.514 ms/op
                 createUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 367395
  mean =      2.610 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 171572 
    [ 2.500,  3.750) = 190948 
    [ 3.750,  5.000) = 3732 
    [ 5.000,  6.250) = 576 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.687 ms/op
     p(90.0000) =      3.174 ms/op
     p(95.0000) =      3.301 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      9.195 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     16.651 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.138 ms/op
                 existUser·p0.95:   3.265 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  5.186 ms/op
                 existUser·p0.9999: 13.984 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.097 ms/op
                 existUser·p0.95:   3.215 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  10.033 ms/op
                 existUser·p0.9999: 19.704 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.121 ms/op
                 existUser·p0.95:   3.252 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  5.902 ms/op
                 existUser·p0.9999: 13.352 ms/op
                 existUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 375723
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180564 
    [ 2.500,  5.000) = 194329 
    [ 5.000,  7.500) = 506 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      5.792 ms/op
     p(99.9900) =     14.949 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.599 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.187 ms/op
                 getUser·p0.95:   3.346 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 13.676 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.600 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   2.638 ms/op
                 getUser·p0.90:   3.162 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.972 ms/op
                 getUser·p0.9999: 13.486 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 2.597 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.166 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 12.611 ms/op
                 getUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 369098
  mean =      2.599 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 176036 
    [ 2.500,  3.750) = 186432 
    [ 3.750,  5.000) = 5011 
    [ 5.000,  6.250) = 1086 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.314 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.151 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.954 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.009 ms/op
Iteration   1: 3.093 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.883 ms/op
                 listUser·p0.999:  9.087 ms/op
                 listUser·p0.9999: 10.846 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   2: 3.082 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.295 ms/op
                 listUser·p0.9999: 10.725 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.874 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 11.125 ms/op
                 listUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309881
  mean =      3.095 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 77093 
    [ 2.500,  3.750) = 187962 
    [ 3.750,  5.000) = 36266 
    [ 5.000,  6.250) = 6757 
    [ 6.250,  7.500) = 1058 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 237 
    [10.000, 11.250) = 195 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     10.945 ms/op
     p(99.9990) =     11.860 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.182 ± 0.286  ops/ms
ClientPb.existUser                       thrpt       3  12.667 ± 1.687  ops/ms
ClientPb.getUser                         thrpt       3  12.504 ± 1.390  ops/ms
ClientPb.listUser                        thrpt       3  10.353 ± 0.622  ops/ms
ClientPb.createUser                       avgt       3   2.607 ± 0.503   ms/op
ClientPb.existUser                        avgt       3   2.504 ± 0.093   ms/op
ClientPb.getUser                          avgt       3   2.560 ± 0.329   ms/op
ClientPb.listUser                         avgt       3   3.054 ± 0.189   ms/op
ClientPb.createUser                     sample  367395   2.610 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.682           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.687           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.195           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.729           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.498           ms/op
ClientPb.existUser                      sample  375723   2.552 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.912           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.601           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.792           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.949           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.906           ms/op
ClientPb.getUser                        sample  369098   2.599 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.490           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.617           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.668           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.418           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.696           ms/op
ClientPb.listUser                       sample  309881   3.095 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.880           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.945           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.157           ms/op
