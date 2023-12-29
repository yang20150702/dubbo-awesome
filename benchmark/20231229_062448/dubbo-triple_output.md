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
# Warmup Iteration   1: 5.027 ops/ms
# Warmup Iteration   2: 12.185 ops/ms
# Warmup Iteration   3: 12.440 ops/ms
Iteration   1: 12.565 ops/ms
Iteration   2: 12.475 ops/ms
Iteration   3: 12.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.543 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (12.475, 12.543, 12.589), stdev = 0.060
  CI (99.9%): [11.447, 13.640] (assumes normal distribution)


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
# Warmup Iteration   1: 8.258 ops/ms
# Warmup Iteration   2: 13.116 ops/ms
# Warmup Iteration   3: 13.091 ops/ms
Iteration   1: 13.120 ops/ms
Iteration   2: 13.167 ops/ms
Iteration   3: 13.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.150 ±(99.9%) 0.474 ops/ms [Average]
  (min, avg, max) = (13.120, 13.150, 13.167), stdev = 0.026
  CI (99.9%): [12.676, 13.623] (assumes normal distribution)


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
# Warmup Iteration   1: 7.407 ops/ms
# Warmup Iteration   2: 12.370 ops/ms
# Warmup Iteration   3: 12.512 ops/ms
Iteration   1: 12.563 ops/ms
Iteration   2: 12.626 ops/ms
Iteration   3: 12.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.609 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (12.563, 12.609, 12.637), stdev = 0.040
  CI (99.9%): [11.881, 13.336] (assumes normal distribution)


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
# Warmup Iteration   1: 6.269 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.479 ±(99.9%) 0.588 ops/ms [Average]
  (min, avg, max) = (10.442, 10.479, 10.503), stdev = 0.032
  CI (99.9%): [9.890, 11.067] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.005 ms/op
Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.526 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (2.524, 2.526, 2.528), stdev = 0.002
  CI (99.9%): [2.489, 2.564] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.003 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.470 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (2.467, 2.470, 2.473), stdev = 0.003
  CI (99.9%): [2.419, 2.522] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.003 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (2.501, 2.514, 2.537), stdev = 0.020
  CI (99.9%): [2.149, 2.878] (assumes normal distribution)


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.004 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
Iteration   3: 2.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.984, 2.992, 2.998), stdev = 0.007
  CI (99.9%): [2.862, 3.122] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  10.746 ms/op
                 createUser·p0.9999: 14.189 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.553 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 12.243 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.742 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 11.445 ms/op
                 createUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382058
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 186426 
    [ 2.500,  3.750) = 192330 
    [ 3.750,  5.000) = 2468 
    [ 5.000,  6.250) = 274 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.830 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  8.188 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  5.038 ms/op
                 existUser·p0.9999: 13.382 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  6.237 ms/op
                 existUser·p0.9999: 11.974 ms/op
                 existUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393880
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 192889 
    [ 2.500,  3.750) = 197873 
    [ 3.750,  5.000) = 2266 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      6.518 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.160 ms/op
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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  8.580 ms/op
                 getUser·p0.9999: 17.007 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  9.824 ms/op
                 getUser·p0.9999: 12.125 ms/op
                 getUser·p1.00:   12.681 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  6.776 ms/op
                 getUser·p0.9999: 11.403 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388838
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 194069 
    [ 2.500,  3.750) = 189815 
    [ 3.750,  5.000) = 3748 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.604 ms/op
     p(99.9900) =     13.963 ms/op
     p(99.9990) =     17.535 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 4.726 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.929 ms/op
                 listUser·p0.9999: 11.005 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   2: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 10.311 ms/op
                 listUser·p1.00:   11.174 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 12.013 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319179
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 96120 
    [ 2.500,  3.750) = 183541 
    [ 3.750,  5.000) = 31036 
    [ 5.000,  6.250) = 6783 
    [ 6.250,  7.500) = 842 
    [ 7.500,  8.750) = 316 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.074 ms/op
     p(99.9900) =     11.093 ms/op
     p(99.9990) =     12.856 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.543 ± 1.096  ops/ms
ClientPb.existUser                       thrpt       3  13.150 ± 0.474  ops/ms
ClientPb.getUser                         thrpt       3  12.609 ± 0.728  ops/ms
ClientPb.listUser                        thrpt       3  10.479 ± 0.588  ops/ms
ClientPb.createUser                       avgt       3   2.526 ± 0.038   ms/op
ClientPb.existUser                        avgt       3   2.470 ± 0.051   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.365   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.130   ms/op
ClientPb.createUser                     sample  382058   2.511 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.872           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  393880   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.893           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.518           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.696           ms/op
ClientPb.getUser                        sample  388838   2.467 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.804           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.604           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.963           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.727           ms/op
ClientPb.listUser                       sample  319179   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.795           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.093           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
