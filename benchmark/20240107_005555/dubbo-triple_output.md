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
# Warmup Iteration   1: 4.984 ops/ms
# Warmup Iteration   2: 12.100 ops/ms
# Warmup Iteration   3: 12.466 ops/ms
Iteration   1: 12.676 ops/ms
Iteration   2: 12.671 ops/ms
Iteration   3: 12.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.635 ±(99.9%) 1.231 ops/ms [Average]
  (min, avg, max) = (12.557, 12.635, 12.676), stdev = 0.067
  CI (99.9%): [11.404, 13.866] (assumes normal distribution)


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
# Warmup Iteration   1: 8.352 ops/ms
# Warmup Iteration   2: 13.087 ops/ms
# Warmup Iteration   3: 13.019 ops/ms
Iteration   1: 13.048 ops/ms
Iteration   2: 13.156 ops/ms
Iteration   3: 13.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.121 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (13.048, 13.121, 13.160), stdev = 0.064
  CI (99.9%): [11.958, 14.284] (assumes normal distribution)


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
# Warmup Iteration   1: 7.837 ops/ms
# Warmup Iteration   2: 12.522 ops/ms
# Warmup Iteration   3: 12.583 ops/ms
Iteration   1: 12.723 ops/ms
Iteration   2: 13.085 ops/ms
Iteration   3: 12.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.877 ±(99.9%) 3.405 ops/ms [Average]
  (min, avg, max) = (12.723, 12.877, 13.085), stdev = 0.187
  CI (99.9%): [9.473, 16.282] (assumes normal distribution)


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
# Warmup Iteration   1: 6.794 ops/ms
# Warmup Iteration   2: 10.511 ops/ms
# Warmup Iteration   3: 10.538 ops/ms
Iteration   1: 10.670 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.697 ±(99.9%) 0.458 ops/ms [Average]
  (min, avg, max) = (10.670, 10.697, 10.719), stdev = 0.025
  CI (99.9%): [10.239, 11.156] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.521, 2.529, 2.536), stdev = 0.008
  CI (99.9%): [2.390, 2.667] (assumes normal distribution)


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.003 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.419 ±(99.9%) 0.003 ms/op
Iteration   3: 2.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.419, 2.427, 2.438), stdev = 0.010
  CI (99.9%): [2.245, 2.608] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.488, 2.494, 2.500), stdev = 0.006
  CI (99.9%): [2.391, 2.597] (assumes normal distribution)


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
# Warmup Iteration   1: 4.796 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.004 ms/op
Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
Iteration   3: 3.003 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.989, 2.996, 3.003), stdev = 0.007
  CI (99.9%): [2.869, 3.122] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  7.189 ms/op
                 createUser·p0.9999: 13.519 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.894 ms/op
                 createUser·p0.9999: 12.210 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  8.656 ms/op
                 createUser·p0.9999: 11.820 ms/op
                 createUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382351
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 185313 
    [ 2.500,  3.750) = 192783 
    [ 3.750,  5.000) = 3284 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     12.677 ms/op
     p(99.9990) =     14.266 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.538 ms/op
                 existUser·p0.9999: 13.295 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  9.271 ms/op
                 existUser·p0.9999: 13.290 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.957 ms/op
                 existUser·p0.999:  6.236 ms/op
                 existUser·p0.9999: 11.567 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389112
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 195022 
    [ 2.500,  3.750) = 189763 
    [ 3.750,  5.000) = 3210 
    [ 5.000,  6.250) = 633 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      6.789 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.833 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  11.297 ms/op
                 getUser·p0.9999: 14.053 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.601 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.461 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 14.726 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  9.119 ms/op
                 getUser·p0.9999: 11.682 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374842
  mean =      2.559 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 180445 
    [ 2.500,  3.750) = 186555 
    [ 3.750,  5.000) = 5847 
    [ 5.000,  6.250) = 1428 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.423 ms/op
     p(99.9900) =     14.115 ms/op
     p(99.9990) =     15.045 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 4.942 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.068 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  9.496 ms/op
                 listUser·p0.9999: 11.579 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.697 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.996 ms/op
                 listUser·p0.9999: 11.166 ms/op
                 listUser·p1.00:   12.288 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.400 ms/op
                 listUser·p0.9999: 10.880 ms/op
                 listUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314750
  mean =      3.047 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 86781 
    [ 2.500,  3.750) = 186011 
    [ 3.750,  5.000) = 33657 
    [ 5.000,  6.250) = 6554 
    [ 6.250,  7.500) = 898 
    [ 7.500,  8.750) = 279 
    [ 8.750, 10.000) = 251 
    [10.000, 11.250) = 181 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     11.207 ms/op
     p(99.9990) =     11.991 ms/op
     p(99.9999) =     12.288 ms/op
    p(100.0000) =     12.288 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.635 ± 1.231  ops/ms
ClientPb.existUser                       thrpt       3  13.121 ± 1.163  ops/ms
ClientPb.getUser                         thrpt       3  12.877 ± 3.405  ops/ms
ClientPb.listUser                        thrpt       3  10.697 ± 0.458  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.138   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.181   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.103   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.127   ms/op
ClientPb.createUser                     sample  382351   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.978           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.651           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.677           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.057           ms/op
ClientPb.existUser                      sample  389112   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.681           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.789           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.107           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.943           ms/op
ClientPb.getUser                        sample  374842   2.559 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.748           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.423           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.115           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.254           ms/op
ClientPb.listUser                       sample  314750   3.047 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.697           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.683           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.207           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.288           ms/op
