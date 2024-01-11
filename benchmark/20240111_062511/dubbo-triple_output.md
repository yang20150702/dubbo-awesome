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
# Warmup Iteration   1: 4.580 ops/ms
# Warmup Iteration   2: 11.813 ops/ms
# Warmup Iteration   3: 12.041 ops/ms
Iteration   1: 12.090 ops/ms
Iteration   2: 12.304 ops/ms
Iteration   3: 12.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.251 ±(99.9%) 2.596 ops/ms [Average]
  (min, avg, max) = (12.090, 12.251, 12.360), stdev = 0.142
  CI (99.9%): [9.656, 14.847] (assumes normal distribution)


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
# Warmup Iteration   1: 8.347 ops/ms
# Warmup Iteration   2: 12.958 ops/ms
# Warmup Iteration   3: 12.951 ops/ms
Iteration   1: 13.122 ops/ms
Iteration   2: 13.071 ops/ms
Iteration   3: 13.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.087 ±(99.9%) 0.566 ops/ms [Average]
  (min, avg, max) = (13.067, 13.087, 13.122), stdev = 0.031
  CI (99.9%): [12.521, 13.652] (assumes normal distribution)


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
# Warmup Iteration   1: 7.749 ops/ms
# Warmup Iteration   2: 12.654 ops/ms
# Warmup Iteration   3: 12.698 ops/ms
Iteration   1: 12.755 ops/ms
Iteration   2: 12.682 ops/ms
Iteration   3: 12.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.686 ±(99.9%) 1.224 ops/ms [Average]
  (min, avg, max) = (12.621, 12.686, 12.755), stdev = 0.067
  CI (99.9%): [11.462, 13.910] (assumes normal distribution)


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
# Warmup Iteration   1: 6.645 ops/ms
# Warmup Iteration   2: 10.394 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.621 ops/ms
Iteration   2: 10.561 ops/ms
Iteration   3: 10.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.551 ±(99.9%) 1.372 ops/ms [Average]
  (min, avg, max) = (10.471, 10.551, 10.621), stdev = 0.075
  CI (99.9%): [9.179, 11.923] (assumes normal distribution)


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.552 ±(99.9%) 0.003 ms/op
Iteration   3: 2.566 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.556 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.551, 2.556, 2.566), stdev = 0.009
  CI (99.9%): [2.401, 2.711] (assumes normal distribution)


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.464, 2.468, 2.475), stdev = 0.006
  CI (99.9%): [2.362, 2.574] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.003 ms/op
Iteration   1: 2.507 ±(99.9%) 0.003 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.505 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.502, 2.505, 2.507), stdev = 0.003
  CI (99.9%): [2.458, 2.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.005 ms/op
Iteration   1: 3.011 ±(99.9%) 0.004 ms/op
Iteration   2: 3.003 ±(99.9%) 0.004 ms/op
Iteration   3: 2.990 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (2.990, 3.001, 3.011), stdev = 0.010
  CI (99.9%): [2.811, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  10.195 ms/op
                 createUser·p0.9999: 13.523 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  8.577 ms/op
                 createUser·p0.9999: 12.190 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 10.379 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382050
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 185317 
    [ 2.500,  3.750) = 192072 
    [ 3.750,  5.000) = 3283 
    [ 5.000,  6.250) = 779 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 151 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.193 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.667 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  7.161 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.513 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  6.170 ms/op
                 existUser·p0.9999: 13.358 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  8.257 ms/op
                 existUser·p0.9999: 11.501 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394714
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 198253 
    [ 2.500,  3.750) = 193355 
    [ 3.750,  5.000) = 2194 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      7.961 ms/op
     p(99.9900) =     13.362 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  11.794 ms/op
                 getUser·p0.9999: 14.798 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 13.139 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  8.229 ms/op
                 getUser·p0.9999: 10.912 ms/op
                 getUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380897
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 187746 
    [ 2.500,  3.750) = 188112 
    [ 3.750,  5.000) = 3939 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      8.290 ms/op
     p(99.9900) =     13.614 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
Iteration   1: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.259 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 11.295 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.500 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 12.573 ms/op
                 listUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318344
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 91992 
    [ 2.500,  3.750) = 186795 
    [ 3.750,  5.000) = 32167 
    [ 5.000,  6.250) = 6004 
    [ 6.250,  7.500) = 576 
    [ 7.500,  8.750) = 168 
    [ 8.750, 10.000) = 309 
    [10.000, 11.250) = 167 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.759 ms/op
     p(99.9900) =     11.501 ms/op
     p(99.9990) =     13.246 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.251 ± 2.596  ops/ms
ClientPb.existUser                       thrpt       3  13.087 ± 0.566  ops/ms
ClientPb.getUser                         thrpt       3  12.686 ± 1.224  ops/ms
ClientPb.listUser                        thrpt       3  10.551 ± 1.372  ops/ms
ClientPb.createUser                       avgt       3   2.556 ± 0.155   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.106   ms/op
ClientPb.getUser                          avgt       3   2.505 ± 0.048   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.190   ms/op
ClientPb.createUser                     sample  382050   2.510 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.526           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.206           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.186           ms/op
ClientPb.existUser                      sample  394714   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.961           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.362           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.090           ms/op
ClientPb.getUser                        sample  380897   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.718           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.290           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.614           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.598           ms/op
ClientPb.listUser                       sample  318344   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.759           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.501           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.337           ms/op
