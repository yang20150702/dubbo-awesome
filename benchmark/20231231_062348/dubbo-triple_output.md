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
# Warmup Iteration   1: 5.123 ops/ms
# Warmup Iteration   2: 11.876 ops/ms
# Warmup Iteration   3: 12.346 ops/ms
Iteration   1: 12.587 ops/ms
Iteration   2: 12.599 ops/ms
Iteration   3: 12.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.640 ±(99.9%) 1.489 ops/ms [Average]
  (min, avg, max) = (12.587, 12.640, 12.734), stdev = 0.082
  CI (99.9%): [11.151, 14.129] (assumes normal distribution)


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
# Warmup Iteration   1: 8.437 ops/ms
# Warmup Iteration   2: 13.226 ops/ms
# Warmup Iteration   3: 13.189 ops/ms
Iteration   1: 12.936 ops/ms
Iteration   2: 13.268 ops/ms
Iteration   3: 13.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.144 ±(99.9%) 3.307 ops/ms [Average]
  (min, avg, max) = (12.936, 13.144, 13.268), stdev = 0.181
  CI (99.9%): [9.838, 16.451] (assumes normal distribution)


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
# Warmup Iteration   1: 7.558 ops/ms
# Warmup Iteration   2: 12.592 ops/ms
# Warmup Iteration   3: 12.847 ops/ms
Iteration   1: 12.844 ops/ms
Iteration   2: 12.845 ops/ms
Iteration   3: 12.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.890 ±(99.9%) 1.445 ops/ms [Average]
  (min, avg, max) = (12.844, 12.890, 12.982), stdev = 0.079
  CI (99.9%): [11.446, 14.335] (assumes normal distribution)


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
# Warmup Iteration   1: 6.781 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.561 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.589 ops/ms
Iteration   3: 10.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.569 ±(99.9%) 0.475 ops/ms [Average]
  (min, avg, max) = (10.539, 10.569, 10.589), stdev = 0.026
  CI (99.9%): [10.094, 11.043] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.531 ±(99.9%) 0.003 ms/op
Iteration   3: 2.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.521, 2.533, 2.547), stdev = 0.013
  CI (99.9%): [2.292, 2.773] (assumes normal distribution)


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
# Warmup Iteration   1: 3.667 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
Iteration   3: 2.474 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (2.472, 2.474, 2.476), stdev = 0.002
  CI (99.9%): [2.434, 2.514] (assumes normal distribution)


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.003 ms/op
Iteration   3: 2.463 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.455 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.450, 2.455, 2.463), stdev = 0.007
  CI (99.9%): [2.327, 2.584] (assumes normal distribution)


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
# Warmup Iteration   1: 4.684 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (3.002, 3.014, 3.035), stdev = 0.018
  CI (99.9%): [2.687, 3.341] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  5.885 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  7.323 ms/op
                 createUser·p0.9999: 12.337 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 10.895 ms/op
                 createUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389441
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 190900 
    [ 2.500,  3.750) = 195416 
    [ 3.750,  5.000) = 2375 
    [ 5.000,  6.250) = 212 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      8.922 ms/op
     p(99.9900) =     13.501 ms/op
     p(99.9990) =     17.991 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.054 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  7.465 ms/op
                 existUser·p0.9999: 13.268 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.812 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 11.600 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391310
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 195252 
    [ 2.500,  3.750) = 192891 
    [ 3.750,  5.000) = 2391 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      6.608 ms/op
     p(99.9900) =     12.933 ms/op
     p(99.9990) =     13.801 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.708 ms/op
                 getUser·p0.999:  6.176 ms/op
                 getUser·p0.9999: 13.766 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  10.296 ms/op
                 getUser·p0.9999: 17.001 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 12.020 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383434
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 189167 
    [ 2.500,  3.750) = 189548 
    [ 3.750,  5.000) = 3550 
    [ 5.000,  6.250) = 595 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     14.150 ms/op
     p(99.9990) =     17.356 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.461 ms/op
                 listUser·p0.9999: 10.590 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   2: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   11.551 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.910 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320854
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 96055 
    [ 2.500,  3.750) = 187419 
    [ 3.750,  5.000) = 30330 
    [ 5.000,  6.250) = 5645 
    [ 6.250,  7.500) = 575 
    [ 7.500,  8.750) = 295 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     10.779 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.640 ± 1.489  ops/ms
ClientPb.existUser                       thrpt       3  13.144 ± 3.307  ops/ms
ClientPb.getUser                         thrpt       3  12.890 ± 1.445  ops/ms
ClientPb.listUser                        thrpt       3  10.569 ± 0.475  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.241   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.040   ms/op
ClientPb.getUser                          avgt       3   2.455 ± 0.128   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.327   ms/op
ClientPb.createUser                     sample  389441   2.463 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.796           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.922           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.501           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.481           ms/op
ClientPb.existUser                      sample  391310   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.898           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.608           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.933           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.992           ms/op
ClientPb.getUser                        sample  383434   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.711           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.142           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.150           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.531           ms/op
ClientPb.listUser                       sample  320854   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.779           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.435           ms/op
