# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.746 ops/ms
# Warmup Iteration   2: 6.469 ops/ms
# Warmup Iteration   3: 8.946 ops/ms
Iteration   1: 9.657 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 9.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.955 ±(99.9%) 5.131 ops/ms [Average]
  (min, avg, max) = (9.657, 9.955, 10.215), stdev = 0.281
  CI (99.9%): [4.824, 15.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ops/ms
# Warmup Iteration   2: 9.402 ops/ms
# Warmup Iteration   3: 9.102 ops/ms
Iteration   1: 10.239 ops/ms
Iteration   2: 10.263 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.372 ±(99.9%) 3.836 ops/ms [Average]
  (min, avg, max) = (10.239, 10.372, 10.615), stdev = 0.210
  CI (99.9%): [6.536, 14.208] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ops/ms
# Warmup Iteration   2: 9.373 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 10.114 ops/ms
Iteration   2: 9.943 ops/ms
Iteration   3: 9.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.949 ±(99.9%) 2.971 ops/ms [Average]
  (min, avg, max) = (9.789, 9.949, 10.114), stdev = 0.163
  CI (99.9%): [6.978, 12.919] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.826 ops/ms
# Warmup Iteration   3: 8.515 ops/ms
Iteration   1: 8.658 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.485 ±(99.9%) 2.910 ops/ms [Average]
  (min, avg, max) = (8.345, 8.485, 8.658), stdev = 0.160
  CI (99.9%): [5.574, 11.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.850 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.004 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
Iteration   3: 3.164 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.126 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.057, 3.126, 3.164), stdev = 0.060
  CI (99.9%): [2.037, 4.215] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.332 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.003 ms/op
Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
Iteration   3: 3.015 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.018 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.015, 3.018, 3.024), stdev = 0.005
  CI (99.9%): [2.920, 3.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
Iteration   3: 3.213 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.126 ±(99.9%) 1.384 ms/op [Average]
  (min, avg, max) = (3.079, 3.126, 3.213), stdev = 0.076
  CI (99.9%): [1.742, 4.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.972 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.004 ms/op
Iteration   1: 3.770 ±(99.9%) 0.003 ms/op
Iteration   2: 3.667 ±(99.9%) 0.010 ms/op
Iteration   3: 3.714 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.717 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.667, 3.717, 3.770), stdev = 0.051
  CI (99.9%): [2.778, 4.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.809 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
Iteration   1: 3.134 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  17.494 ms/op
                 createUser·p0.9999: 22.177 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.275 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 22.644 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 3.338 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  13.959 ms/op
                 createUser·p0.9999: 18.830 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297573
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27447 
    [ 2.500,  5.000) = 262010 
    [ 5.000,  7.500) = 7160 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.275 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.737 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.124 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.423 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.009 ms/op
Iteration   1: 3.074 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.593 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 33.735 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  8.824 ms/op
                 existUser·p0.9999: 22.309 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.326 ms/op
                 existUser·p0.99:   5.206 ms/op
                 existUser·p0.999:  11.059 ms/op
                 existUser·p0.9999: 21.066 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311487
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26480 
    [ 2.500,  5.000) = 280336 
    [ 5.000,  7.500) = 3996 
    [ 7.500, 10.000) = 295 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     11.010 ms/op
     p(99.9900) =     31.745 ms/op
     p(99.9990) =     34.485 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.531 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
Iteration   1: 3.175 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  15.657 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 3.167 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.455 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  12.661 ms/op
                 getUser·p0.9999: 33.686 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  16.628 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301887
  mean =      3.179 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15173 
    [ 2.500,  5.000) = 280274 
    [ 5.000,  7.500) = 5468 
    [ 7.500, 10.000) = 505 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     33.143 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.606 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 18.921 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 3.766 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   7.328 ms/op
                 listUser·p0.999:  14.437 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   3: 3.693 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  11.829 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257377
  mean =      3.728 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 248608 
    [ 5.000,  7.500) = 6714 
    [ 7.500, 10.000) = 1205 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.773 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.955 ± 5.131  ops/ms
ClientPb.existUser                       thrpt       3  10.372 ± 3.836  ops/ms
ClientPb.getUser                         thrpt       3   9.949 ± 2.971  ops/ms
ClientPb.listUser                        thrpt       3   8.485 ± 2.910  ops/ms
ClientPb.createUser                       avgt       3   3.126 ± 1.089   ms/op
ClientPb.existUser                        avgt       3   3.018 ± 0.099   ms/op
ClientPb.getUser                          avgt       3   3.126 ± 1.384   ms/op
ClientPb.listUser                         avgt       3   3.717 ± 0.939   ms/op
ClientPb.createUser                     sample  297573   3.225 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.275           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.737           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.024           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.086           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.478           ms/op
ClientPb.existUser                      sample  311487   3.080 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.272           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.010           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.745           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  301887   3.179 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.455           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.718           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.450           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.143           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.144           ms/op
ClientPb.listUser                       sample  257377   3.728 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.442           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.955           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.773           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.365           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.167           ms/op
