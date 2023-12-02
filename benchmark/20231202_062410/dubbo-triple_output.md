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
# Warmup Iteration   1: 4.789 ops/ms
# Warmup Iteration   2: 11.942 ops/ms
# Warmup Iteration   3: 12.111 ops/ms
Iteration   1: 12.399 ops/ms
Iteration   2: 12.417 ops/ms
Iteration   3: 12.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.411 ±(99.9%) 0.180 ops/ms [Average]
  (min, avg, max) = (12.399, 12.411, 12.417), stdev = 0.010
  CI (99.9%): [12.230, 12.591] (assumes normal distribution)


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
# Warmup Iteration   1: 8.327 ops/ms
# Warmup Iteration   2: 12.965 ops/ms
# Warmup Iteration   3: 12.911 ops/ms
Iteration   1: 13.082 ops/ms
Iteration   2: 12.933 ops/ms
Iteration   3: 12.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.956 ±(99.9%) 2.116 ops/ms [Average]
  (min, avg, max) = (12.854, 12.956, 13.082), stdev = 0.116
  CI (99.9%): [10.841, 15.072] (assumes normal distribution)


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
# Warmup Iteration   1: 7.781 ops/ms
# Warmup Iteration   2: 12.354 ops/ms
# Warmup Iteration   3: 12.550 ops/ms
Iteration   1: 12.616 ops/ms
Iteration   2: 12.593 ops/ms
Iteration   3: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.603 ±(99.9%) 0.226 ops/ms [Average]
  (min, avg, max) = (12.593, 12.603, 12.616), stdev = 0.012
  CI (99.9%): [12.377, 12.828] (assumes normal distribution)


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
# Warmup Iteration   1: 6.728 ops/ms
# Warmup Iteration   2: 10.408 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.559 ±(99.9%) 0.557 ops/ms [Average]
  (min, avg, max) = (10.530, 10.559, 10.591), stdev = 0.031
  CI (99.9%): [10.002, 11.115] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.575 ±(99.9%) 0.003 ms/op
Iteration   1: 2.581 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
Iteration   3: 2.551 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (2.538, 2.557, 2.581), stdev = 0.022
  CI (99.9%): [2.150, 2.963] (assumes normal distribution)


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
# Warmup Iteration   1: 3.934 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.487 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (2.465, 2.487, 2.501), stdev = 0.019
  CI (99.9%): [2.135, 2.839] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.535 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.528 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.521, 2.528, 2.535), stdev = 0.007
  CI (99.9%): [2.398, 2.657] (assumes normal distribution)


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
# Warmup Iteration   1: 4.824 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.005 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
Iteration   3: 3.057 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.048 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (3.037, 3.048, 3.057), stdev = 0.010
  CI (99.9%): [2.867, 3.228] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.584 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  11.036 ms/op
                 createUser·p0.9999: 14.025 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 12.488 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.609 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  9.415 ms/op
                 createUser·p0.9999: 11.104 ms/op
                 createUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370098
  mean =      2.591 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 173341 
    [ 2.500,  3.750) = 190767 
    [ 3.750,  5.000) = 4863 
    [ 5.000,  6.250) = 606 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.305 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =      9.583 ms/op
     p(99.9900) =     12.992 ms/op
     p(99.9990) =     14.775 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  6.076 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  6.153 ms/op
                 existUser·p0.9999: 13.340 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  7.133 ms/op
                 existUser·p0.9999: 12.914 ms/op
                 existUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387051
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 191977 
    [ 2.500,  3.750) = 191267 
    [ 3.750,  5.000) = 3043 
    [ 5.000,  6.250) = 339 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      6.144 ms/op
     p(99.9900) =     15.488 ms/op
     p(99.9990) =     16.917 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  11.796 ms/op
                 getUser·p0.9999: 13.528 ms/op
                 getUser·p1.00:   15.417 ms/op

Iteration   2: 2.571 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  9.366 ms/op
                 getUser·p0.9999: 15.627 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  8.676 ms/op
                 getUser·p0.9999: 11.915 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376314
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 183699 
    [ 2.500,  3.750) = 187160 
    [ 3.750,  5.000) = 4215 
    [ 5.000,  6.250) = 712 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     16.060 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 5.041 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.009 ms/op
Iteration   1: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.922 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.041 ms/op
                 listUser·p0.9999: 12.051 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.631 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 13.369 ms/op
                 listUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313418
  mean =      3.060 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 83718 
    [ 2.500,  3.750) = 187482 
    [ 3.750,  5.000) = 34636 
    [ 5.000,  6.250) = 5913 
    [ 6.250,  7.500) = 904 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     12.517 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.411 ± 0.180  ops/ms
ClientPb.existUser                       thrpt       3  12.956 ± 2.116  ops/ms
ClientPb.getUser                         thrpt       3  12.603 ± 0.226  ops/ms
ClientPb.listUser                        thrpt       3  10.559 ± 0.557  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.406   ms/op
ClientPb.existUser                        avgt       3   2.487 ± 0.352   ms/op
ClientPb.getUser                          avgt       3   2.528 ± 0.130   ms/op
ClientPb.listUser                         avgt       3   3.048 ± 0.181   ms/op
ClientPb.createUser                     sample  370098   2.591 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.866           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.583           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.992           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  387051   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.831           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.144           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.488           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.072           ms/op
ClientPb.getUser                        sample  376314   2.549 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.833           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.700           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.204           ms/op
ClientPb.listUser                       sample  313418   3.060 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.631           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.517           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.041           ms/op
