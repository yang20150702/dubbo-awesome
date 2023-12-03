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
# Warmup Iteration   1: 5.139 ops/ms
# Warmup Iteration   2: 12.231 ops/ms
# Warmup Iteration   3: 12.468 ops/ms
Iteration   1: 12.585 ops/ms
Iteration   2: 12.644 ops/ms
Iteration   3: 12.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.574 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (12.491, 12.574, 12.644), stdev = 0.077
  CI (99.9%): [11.163, 13.985] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 8.274 ops/ms
# Warmup Iteration   2: 12.930 ops/ms
# Warmup Iteration   3: 13.142 ops/ms
Iteration   1: 12.914 ops/ms
Iteration   2: 13.010 ops/ms
Iteration   3: 13.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.009 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (12.914, 13.009, 13.102), stdev = 0.094
  CI (99.9%): [11.293, 14.724] (assumes normal distribution)


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
# Warmup Iteration   1: 8.087 ops/ms
# Warmup Iteration   2: 12.526 ops/ms
# Warmup Iteration   3: 12.825 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.773 ops/ms
Iteration   3: 12.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.756 ±(99.9%) 0.477 ops/ms [Average]
  (min, avg, max) = (12.726, 12.756, 12.773), stdev = 0.026
  CI (99.9%): [12.279, 13.233] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.714 ops/ms
# Warmup Iteration   2: 10.544 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 10.762 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.697 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (10.579, 10.697, 10.762), stdev = 0.102
  CI (99.9%): [8.835, 12.558] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
Iteration   1: 2.548 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.537 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.517, 2.537, 2.548), stdev = 0.017
  CI (99.9%): [2.220, 2.853] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.672 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.003 ms/op
Iteration   1: 2.447 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.447, 2.460, 2.469), stdev = 0.011
  CI (99.9%): [2.250, 2.669] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (2.489, 2.510, 2.526), stdev = 0.019
  CI (99.9%): [2.163, 2.857] (assumes normal distribution)


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.004 ms/op
Iteration   1: 2.992 ±(99.9%) 0.004 ms/op
Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
Iteration   3: 2.973 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.973, 2.987, 2.997), stdev = 0.013
  CI (99.9%): [2.759, 3.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  7.476 ms/op
                 createUser·p0.9999: 13.050 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  9.022 ms/op
                 createUser·p0.9999: 11.999 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  8.314 ms/op
                 createUser·p0.9999: 10.539 ms/op
                 createUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384466
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 188334 
    [ 2.500,  3.750) = 192160 
    [ 3.750,  5.000) = 3070 
    [ 5.000,  6.250) = 301 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.291 ms/op
     p(99.9900) =     12.617 ms/op
     p(99.9990) =     13.434 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  6.922 ms/op
                 existUser·p0.9999: 13.744 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 12.750 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  7.755 ms/op
                 existUser·p0.9999: 11.631 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393064
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 194392 
    [ 2.500,  3.750) = 195081 
    [ 3.750,  5.000) = 2792 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.237 ms/op
     p(99.9900) =     13.295 ms/op
     p(99.9990) =     14.437 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  11.282 ms/op
                 getUser·p0.9999: 13.537 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  9.666 ms/op
                 getUser·p0.9999: 17.498 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.649 ms/op
                 getUser·p0.9999: 10.366 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382213
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 188174 
    [ 2.500,  3.750) = 188333 
    [ 3.750,  5.000) = 4612 
    [ 5.000,  6.250) = 581 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 154 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =      8.660 ms/op
     p(99.9900) =     14.074 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 4.946 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.811 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 10.135 ms/op
                 listUser·p1.00:   10.551 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.723 ms/op
                 listUser·p0.9999: 16.581 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.320 ms/op
                 listUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317004
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 90012 
    [ 2.500,  3.750) = 186754 
    [ 3.750,  5.000) = 32393 
    [ 5.000,  6.250) = 6511 
    [ 6.250,  7.500) = 536 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 294 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     14.356 ms/op
     p(99.9990) =     17.267 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.574 ± 1.411  ops/ms
ClientPb.existUser                       thrpt       3  13.009 ± 1.716  ops/ms
ClientPb.getUser                         thrpt       3  12.756 ± 0.477  ops/ms
ClientPb.listUser                        thrpt       3  10.697 ± 1.862  ops/ms
ClientPb.createUser                       avgt       3   2.537 ± 0.316   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.210   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.347   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.229   ms/op
ClientPb.createUser                     sample  384466   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.850           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.291           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.617           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.861           ms/op
ClientPb.existUser                      sample  393064   2.440 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.729           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.237           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.295           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  382213   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.947           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.660           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.074           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.416           ms/op
ClientPb.listUser                       sample  317004   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.792           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.356           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.498           ms/op
