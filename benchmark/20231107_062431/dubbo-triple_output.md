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
# Warmup Iteration   1: 4.571 ops/ms
# Warmup Iteration   2: 11.963 ops/ms
# Warmup Iteration   3: 12.357 ops/ms
Iteration   1: 12.565 ops/ms
Iteration   2: 12.756 ops/ms
Iteration   3: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.642 ±(99.9%) 1.846 ops/ms [Average]
  (min, avg, max) = (12.565, 12.642, 12.756), stdev = 0.101
  CI (99.9%): [10.796, 14.488] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.173 ops/ms
# Warmup Iteration   2: 12.979 ops/ms
# Warmup Iteration   3: 12.934 ops/ms
Iteration   1: 12.882 ops/ms
Iteration   2: 13.140 ops/ms
Iteration   3: 13.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.048 ±(99.9%) 2.626 ops/ms [Average]
  (min, avg, max) = (12.882, 13.048, 13.140), stdev = 0.144
  CI (99.9%): [10.422, 15.674] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.584 ops/ms
# Warmup Iteration   2: 12.451 ops/ms
# Warmup Iteration   3: 12.554 ops/ms
Iteration   1: 12.551 ops/ms
Iteration   2: 12.676 ops/ms
Iteration   3: 12.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.644 ±(99.9%) 1.493 ops/ms [Average]
  (min, avg, max) = (12.551, 12.644, 12.705), stdev = 0.082
  CI (99.9%): [11.151, 14.137] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.568 ops/ms
# Warmup Iteration   2: 10.354 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.470 ops/ms
Iteration   3: 10.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.468 ±(99.9%) 2.318 ops/ms [Average]
  (min, avg, max) = (10.340, 10.468, 10.595), stdev = 0.127
  CI (99.9%): [8.151, 12.786] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.003 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
Iteration   3: 2.553 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.534, 2.549, 2.560), stdev = 0.014
  CI (99.9%): [2.300, 2.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.438, 2.451, 2.469), stdev = 0.016
  CI (99.9%): [2.164, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (2.484, 2.488, 2.492), stdev = 0.004
  CI (99.9%): [2.419, 2.558] (assumes normal distribution)


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
# Warmup Iteration   1: 4.705 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
Iteration   3: 2.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (2.984, 2.991, 3.002), stdev = 0.010
  CI (99.9%): [2.812, 3.169] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.926 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 14.753 ms/op
                 createUser·p1.00:   15.368 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  7.569 ms/op
                 createUser·p0.9999: 11.977 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 10.910 ms/op
                 createUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383392
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 185022 
    [ 2.500,  3.750) = 194013 
    [ 3.750,  5.000) = 3330 
    [ 5.000,  6.250) = 507 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.982 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     15.213 ms/op
     p(99.9999) =     15.368 ms/op
    p(100.0000) =     15.368 ms/op


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  7.287 ms/op
                 existUser·p0.9999: 13.516 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.283 ms/op
                 existUser·p0.9999: 11.812 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  8.924 ms/op
                 existUser·p0.9999: 12.631 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391712
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 195331 
    [ 2.500,  3.750) = 191841 
    [ 3.750,  5.000) = 3197 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      7.318 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     13.765 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.999 ms/op
                 getUser·p0.999:  12.415 ms/op
                 getUser·p0.9999: 17.966 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  9.227 ms/op
                 getUser·p0.9999: 14.172 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  8.795 ms/op
                 getUser·p0.9999: 12.114 ms/op
                 getUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381274
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 187667 
    [ 2.500,  3.750) = 186649 
    [ 3.750,  5.000) = 4794 
    [ 5.000,  6.250) = 1541 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.843 ms/op
     p(99.9900) =     14.508 ms/op
     p(99.9990) =     18.626 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.634 ms/op
                 listUser·p0.999:  9.114 ms/op
                 listUser·p0.9999: 11.516 ms/op
                 listUser·p1.00:   12.026 ms/op

Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  10.076 ms/op
                 listUser·p0.9999: 14.696 ms/op
                 listUser·p1.00:   16.351 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 11.390 ms/op
                 listUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315133
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 87966 
    [ 2.500,  3.750) = 185317 
    [ 3.750,  5.000) = 33524 
    [ 5.000,  6.250) = 6713 
    [ 6.250,  7.500) = 777 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 295 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     14.278 ms/op
     p(99.9990) =     15.557 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.642 ± 1.846  ops/ms
ClientPb.existUser                       thrpt       3  13.048 ± 2.626  ops/ms
ClientPb.getUser                         thrpt       3  12.644 ± 1.493  ops/ms
ClientPb.listUser                        thrpt       3  10.468 ± 2.318  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.249   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.287   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.070   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.179   ms/op
ClientPb.createUser                     sample  383392   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.903           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.982           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.648           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.368           ms/op
ClientPb.existUser                      sample  391712   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.318           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.271           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.139           ms/op
ClientPb.getUser                        sample  381274   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.801           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.508           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.071           ms/op
ClientPb.listUser                       sample  315133   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.816           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.278           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.351           ms/op
