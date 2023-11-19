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
# Warmup Iteration   1: 4.903 ops/ms
# Warmup Iteration   2: 11.952 ops/ms
# Warmup Iteration   3: 12.358 ops/ms
Iteration   1: 12.588 ops/ms
Iteration   2: 12.588 ops/ms
Iteration   3: 12.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.648 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (12.588, 12.648, 12.767), stdev = 0.103
  CI (99.9%): [10.761, 14.534] (assumes normal distribution)


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
# Warmup Iteration   1: 8.067 ops/ms
# Warmup Iteration   2: 13.005 ops/ms
# Warmup Iteration   3: 13.052 ops/ms
Iteration   1: 13.063 ops/ms
Iteration   2: 13.233 ops/ms
Iteration   3: 13.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.101 ±(99.9%) 2.156 ops/ms [Average]
  (min, avg, max) = (13.006, 13.101, 13.233), stdev = 0.118
  CI (99.9%): [10.945, 15.257] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.816 ops/ms
# Warmup Iteration   2: 12.451 ops/ms
# Warmup Iteration   3: 12.816 ops/ms
Iteration   1: 12.710 ops/ms
Iteration   2: 12.794 ops/ms
Iteration   3: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.761 ±(99.9%) 0.822 ops/ms [Average]
  (min, avg, max) = (12.710, 12.761, 12.794), stdev = 0.045
  CI (99.9%): [11.939, 13.583] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.366 ops/ms
# Warmup Iteration   2: 10.389 ops/ms
# Warmup Iteration   3: 10.530 ops/ms
Iteration   1: 10.645 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.567 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (10.479, 10.567, 10.645), stdev = 0.083
  CI (99.9%): [9.046, 12.088] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.005 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (2.508, 2.524, 2.537), stdev = 0.015
  CI (99.9%): [2.250, 2.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.403 ±(99.9%) 0.003 ms/op
Iteration   1: 2.420 ±(99.9%) 0.004 ms/op
Iteration   2: 2.414 ±(99.9%) 0.003 ms/op
Iteration   3: 2.389 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.408 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.389, 2.408, 2.420), stdev = 0.016
  CI (99.9%): [2.110, 2.705] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.003 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.462, 2.477, 2.489), stdev = 0.014
  CI (99.9%): [2.226, 2.727] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.858 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
Iteration   3: 3.030 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (3.025, 3.033, 3.043), stdev = 0.010
  CI (99.9%): [2.859, 3.207] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.415 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.704 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  12.644 ms/op
                 createUser·p0.9999: 15.879 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  10.043 ms/op
                 createUser·p0.9999: 14.555 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.853 ms/op
                 createUser·p0.999:  7.803 ms/op
                 createUser·p0.9999: 10.355 ms/op
                 createUser·p1.00:   10.650 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382345
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 183415 
    [ 2.500,  3.750) = 193716 
    [ 3.750,  5.000) = 3815 
    [ 5.000,  6.250) = 785 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     14.643 ms/op
     p(99.9990) =     16.108 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.781 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 16.450 ms/op
                 existUser·p1.00:   16.630 ms/op

Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  8.448 ms/op
                 existUser·p0.9999: 15.583 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  8.654 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387562
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 190941 
    [ 2.500,  3.750) = 192284 
    [ 3.750,  5.000) = 3346 
    [ 5.000,  6.250) = 468 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      7.462 ms/op
     p(99.9900) =     15.397 ms/op
     p(99.9990) =     16.599 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  11.914 ms/op
                 getUser·p0.9999: 16.144 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.347 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.018 ms/op
                 getUser·p0.999:  9.832 ms/op
                 getUser·p0.9999: 13.234 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.328 ms/op
                 getUser·p0.999:  8.606 ms/op
                 getUser·p0.9999: 11.588 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382833
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 187621 
    [ 2.500,  3.750) = 188637 
    [ 3.750,  5.000) = 4849 
    [ 5.000,  6.250) = 1077 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      9.063 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     16.765 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.762 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.009 ms/op
Iteration   1: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 13.039 ms/op
                 listUser·p1.00:   13.599 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.961 ms/op
                 listUser·p1.00:   12.583 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.925 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 12.767 ms/op
                 listUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317887
  mean =      3.017 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 93196 
    [ 2.500,  3.750) = 183946 
    [ 3.750,  5.000) = 32843 
    [ 5.000,  6.250) = 6325 
    [ 6.250,  7.500) = 803 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.226 ms/op
     p(99.9900) =     12.767 ms/op
     p(99.9990) =     13.527 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.648 ± 1.887  ops/ms
ClientPb.existUser                       thrpt       3  13.101 ± 2.156  ops/ms
ClientPb.getUser                         thrpt       3  12.761 ± 0.822  ops/ms
ClientPb.listUser                        thrpt       3  10.567 ± 1.521  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.274   ms/op
ClientPb.existUser                        avgt       3   2.408 ± 0.298   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.251   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.174   ms/op
ClientPb.createUser                     sample  382345   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.591           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.643           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.679           ms/op
ClientPb.existUser                      sample  387562   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.862           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.462           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.397           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.630           ms/op
ClientPb.getUser                        sample  382833   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.347           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.063           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.320           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.465           ms/op
ClientPb.listUser                       sample  317887   3.017 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.779           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.226           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.767           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.599           ms/op
