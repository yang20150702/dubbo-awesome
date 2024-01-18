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
# Warmup Iteration   1: 4.197 ops/ms
# Warmup Iteration   2: 11.859 ops/ms
# Warmup Iteration   3: 12.330 ops/ms
Iteration   1: 12.508 ops/ms
Iteration   2: 12.630 ops/ms
Iteration   3: 12.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.633 ±(99.9%) 2.313 ops/ms [Average]
  (min, avg, max) = (12.508, 12.633, 12.762), stdev = 0.127
  CI (99.9%): [10.320, 14.946] (assumes normal distribution)


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
# Warmup Iteration   1: 7.408 ops/ms
# Warmup Iteration   2: 13.002 ops/ms
# Warmup Iteration   3: 12.917 ops/ms
Iteration   1: 12.866 ops/ms
Iteration   2: 13.012 ops/ms
Iteration   3: 12.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.959 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (12.866, 12.959, 13.012), stdev = 0.081
  CI (99.9%): [11.483, 14.435] (assumes normal distribution)


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
# Warmup Iteration   1: 7.638 ops/ms
# Warmup Iteration   2: 12.811 ops/ms
# Warmup Iteration   3: 12.871 ops/ms
Iteration   1: 12.976 ops/ms
Iteration   2: 12.915 ops/ms
Iteration   3: 12.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.927 ±(99.9%) 0.799 ops/ms [Average]
  (min, avg, max) = (12.891, 12.927, 12.976), stdev = 0.044
  CI (99.9%): [12.129, 13.726] (assumes normal distribution)


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
# Warmup Iteration   1: 6.497 ops/ms
# Warmup Iteration   2: 10.458 ops/ms
# Warmup Iteration   3: 10.319 ops/ms
Iteration   1: 10.543 ops/ms
Iteration   2: 10.570 ops/ms
Iteration   3: 10.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.549 ±(99.9%) 0.347 ops/ms [Average]
  (min, avg, max) = (10.534, 10.549, 10.570), stdev = 0.019
  CI (99.9%): [10.203, 10.896] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.570 ±(99.9%) 0.005 ms/op
Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
Iteration   3: 2.484 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.517 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (2.484, 2.517, 2.570), stdev = 0.046
  CI (99.9%): [1.673, 3.362] (assumes normal distribution)


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
Iteration   2: 2.424 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (2.424, 2.430, 2.437), stdev = 0.006
  CI (99.9%): [2.312, 2.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.541 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.529, 2.541, 2.552), stdev = 0.011
  CI (99.9%): [2.333, 2.750] (assumes normal distribution)


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
Iteration   3: 3.011 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.003 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (2.999, 3.003, 3.011), stdev = 0.007
  CI (99.9%): [2.880, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.571 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.490 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  12.063 ms/op
                 createUser·p0.9999: 13.847 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  9.407 ms/op
                 createUser·p0.9999: 14.451 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   3: 2.597 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 15.313 ms/op
                 createUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372609
  mean =      2.573 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 176593 
    [ 2.500,  3.750) = 190816 
    [ 3.750,  5.000) = 3936 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     14.451 ms/op
     p(99.9990) =     15.738 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.645 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  6.612 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  7.864 ms/op
                 existUser·p0.9999: 13.136 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  9.063 ms/op
                 existUser·p0.9999: 11.876 ms/op
                 existUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392608
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 198267 
    [ 2.500,  3.750) = 190944 
    [ 3.750,  5.000) = 2430 
    [ 5.000,  6.250) = 422 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      8.665 ms/op
     p(99.9900) =     13.316 ms/op
     p(99.9990) =     14.002 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  5.925 ms/op
                 getUser·p0.9999: 15.155 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  6.820 ms/op
                 getUser·p0.9999: 13.278 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.184 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  9.057 ms/op
                 getUser·p0.9999: 12.354 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383740
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 189932 
    [ 2.500,  3.750) = 187992 
    [ 3.750,  5.000) = 4495 
    [ 5.000,  6.250) = 785 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      6.866 ms/op
     p(99.9900) =     13.756 ms/op
     p(99.9990) =     15.573 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 4.676 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.485 ms/op
                 listUser·p0.9999: 11.829 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   2: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.909 ms/op
                 listUser·p0.9999: 13.802 ms/op
                 listUser·p1.00:   14.533 ms/op

Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.676 ms/op
                 listUser·p0.9999: 11.638 ms/op
                 listUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318762
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 90022 
    [ 2.500,  3.750) = 189631 
    [ 3.750,  5.000) = 32540 
    [ 5.000,  6.250) = 5273 
    [ 6.250,  7.500) = 539 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 186 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.359 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.029 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.633 ± 2.313  ops/ms
ClientPb.existUser                       thrpt       3  12.959 ± 1.476  ops/ms
ClientPb.getUser                         thrpt       3  12.927 ± 0.799  ops/ms
ClientPb.listUser                        thrpt       3  10.549 ± 0.347  ops/ms
ClientPb.createUser                       avgt       3   2.517 ± 0.844   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.118   ms/op
ClientPb.getUser                          avgt       3   2.541 ± 0.209   ms/op
ClientPb.listUser                         avgt       3   3.003 ± 0.123   ms/op
ClientPb.createUser                     sample  372609   2.573 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.490           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.454           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.451           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.827           ms/op
ClientPb.existUser                      sample  392608   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.858           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.665           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.316           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.418           ms/op
ClientPb.getUser                        sample  383740   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.564           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.866           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.756           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.663           ms/op
ClientPb.listUser                       sample  318762   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.824           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.359           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.271           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.533           ms/op
