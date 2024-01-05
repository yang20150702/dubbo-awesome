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
# Warmup Iteration   1: 4.593 ops/ms
# Warmup Iteration   2: 11.945 ops/ms
# Warmup Iteration   3: 12.321 ops/ms
Iteration   1: 12.522 ops/ms
Iteration   2: 12.557 ops/ms
Iteration   3: 12.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.549 ±(99.9%) 0.444 ops/ms [Average]
  (min, avg, max) = (12.522, 12.549, 12.569), stdev = 0.024
  CI (99.9%): [12.105, 12.993] (assumes normal distribution)


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
# Warmup Iteration   1: 7.912 ops/ms
# Warmup Iteration   2: 13.213 ops/ms
# Warmup Iteration   3: 13.212 ops/ms
Iteration   1: 13.138 ops/ms
Iteration   2: 13.116 ops/ms
Iteration   3: 13.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.112 ±(99.9%) 0.501 ops/ms [Average]
  (min, avg, max) = (13.083, 13.112, 13.138), stdev = 0.027
  CI (99.9%): [12.612, 13.613] (assumes normal distribution)


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
# Warmup Iteration   1: 8.253 ops/ms
# Warmup Iteration   2: 12.612 ops/ms
# Warmup Iteration   3: 12.863 ops/ms
Iteration   1: 12.882 ops/ms
Iteration   2: 12.908 ops/ms
Iteration   3: 12.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.851 ±(99.9%) 1.406 ops/ms [Average]
  (min, avg, max) = (12.764, 12.851, 12.908), stdev = 0.077
  CI (99.9%): [11.445, 14.258] (assumes normal distribution)


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
# Warmup Iteration   1: 6.511 ops/ms
# Warmup Iteration   2: 10.400 ops/ms
# Warmup Iteration   3: 10.629 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.589 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (10.512, 10.589, 10.646), stdev = 0.069
  CI (99.9%): [9.331, 11.847] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.499, 2.514, 2.528), stdev = 0.015
  CI (99.9%): [2.243, 2.785] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.435, 2.447, 2.462), stdev = 0.014
  CI (99.9%): [2.193, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.503, 2.506, 2.511), stdev = 0.004
  CI (99.9%): [2.434, 2.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.005 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
Iteration   3: 2.961 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.961, 2.973, 2.985), stdev = 0.012
  CI (99.9%): [2.752, 3.195] (assumes normal distribution)


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  11.165 ms/op
                 createUser·p0.9999: 13.713 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  8.860 ms/op
                 createUser·p0.9999: 12.777 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  8.727 ms/op
                 createUser·p0.9999: 11.025 ms/op
                 createUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376871
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 180933 
    [ 2.500,  3.750) = 191652 
    [ 3.750,  5.000) = 3546 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.735 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.471 ms/op
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
# Warmup Iteration   1: 3.561 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  5.715 ms/op
                 existUser·p0.9999: 14.118 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  7.501 ms/op
                 existUser·p0.9999: 13.988 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  8.220 ms/op
                 existUser·p0.9999: 11.253 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393731
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 197593 
    [ 2.500,  3.750) = 192728 
    [ 3.750,  5.000) = 2558 
    [ 5.000,  6.250) = 316 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      8.074 ms/op
     p(99.9900) =     13.920 ms/op
     p(99.9990) =     14.517 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  11.726 ms/op
                 getUser·p0.9999: 13.995 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  8.746 ms/op
                 getUser·p0.9999: 13.683 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  6.365 ms/op
                 getUser·p0.9999: 11.436 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385597
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 192010 
    [ 2.500,  3.750) = 189224 
    [ 3.750,  5.000) = 3348 
    [ 5.000,  6.250) = 503 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 137 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.729 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.732 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.841 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.323 ms/op
                 listUser·p0.9999: 10.781 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 11.946 ms/op
                 listUser·p1.00:   13.353 ms/op

Iteration   3: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.608 ms/op
                 listUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317083
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 85954 
    [ 2.500,  3.750) = 191702 
    [ 3.750,  5.000) = 32488 
    [ 5.000,  6.250) = 5652 
    [ 6.250,  7.500) = 560 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 296 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.123 ms/op
     p(99.9990) =     12.206 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.549 ± 0.444  ops/ms
ClientPb.existUser                       thrpt       3  13.112 ± 0.501  ops/ms
ClientPb.getUser                         thrpt       3  12.851 ± 1.406  ops/ms
ClientPb.listUser                        thrpt       3  10.589 ± 1.258  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.271   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.254   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.072   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.222   ms/op
ClientPb.createUser                     sample  376871   2.545 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.890           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.735           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.206           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  393731   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.937           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.920           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.696           ms/op
ClientPb.getUser                        sample  385597   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.041           ms/op
ClientPb.listUser                       sample  317083   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.123           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.353           ms/op
