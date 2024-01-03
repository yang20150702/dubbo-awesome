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
# Warmup Iteration   1: 4.874 ops/ms
# Warmup Iteration   2: 11.719 ops/ms
# Warmup Iteration   3: 12.154 ops/ms
Iteration   1: 12.330 ops/ms
Iteration   2: 12.307 ops/ms
Iteration   3: 12.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.293 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (12.243, 12.293, 12.330), stdev = 0.045
  CI (99.9%): [11.465, 13.121] (assumes normal distribution)


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
# Warmup Iteration   1: 7.925 ops/ms
# Warmup Iteration   2: 12.915 ops/ms
# Warmup Iteration   3: 12.907 ops/ms
Iteration   1: 13.025 ops/ms
Iteration   2: 12.831 ops/ms
Iteration   3: 12.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.943 ±(99.9%) 1.826 ops/ms [Average]
  (min, avg, max) = (12.831, 12.943, 13.025), stdev = 0.100
  CI (99.9%): [11.116, 14.769] (assumes normal distribution)


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
# Warmup Iteration   1: 7.894 ops/ms
# Warmup Iteration   2: 12.288 ops/ms
# Warmup Iteration   3: 12.696 ops/ms
Iteration   1: 12.634 ops/ms
Iteration   2: 12.655 ops/ms
Iteration   3: 12.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.642 ±(99.9%) 0.220 ops/ms [Average]
  (min, avg, max) = (12.634, 12.642, 12.655), stdev = 0.012
  CI (99.9%): [12.422, 12.861] (assumes normal distribution)


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
# Warmup Iteration   1: 6.443 ops/ms
# Warmup Iteration   2: 10.403 ops/ms
# Warmup Iteration   3: 10.528 ops/ms
Iteration   1: 10.550 ops/ms
Iteration   2: 10.495 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.547 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (10.495, 10.547, 10.597), stdev = 0.051
  CI (99.9%): [9.610, 11.485] (assumes normal distribution)


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
# Warmup Iteration   1: 4.226 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
Iteration   1: 2.561 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.003 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (2.510, 2.542, 2.561), stdev = 0.028
  CI (99.9%): [2.038, 3.045] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.003 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.470 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.459, 2.470, 2.488), stdev = 0.016
  CI (99.9%): [2.175, 2.765] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.003 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.506, 2.515, 2.534), stdev = 0.016
  CI (99.9%): [2.219, 2.812] (assumes normal distribution)


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
# Warmup Iteration   1: 4.780 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.004 ms/op
Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
Iteration   3: 3.009 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.009, 3.023, 3.030), stdev = 0.012
  CI (99.9%): [2.811, 3.234] (assumes normal distribution)


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.724 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  11.457 ms/op
                 createUser·p0.9999: 14.555 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  9.444 ms/op
                 createUser·p0.9999: 13.078 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.864 ms/op
                 createUser·p0.9999: 10.606 ms/op
                 createUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380965
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 184221 
    [ 2.500,  3.750) = 193036 
    [ 3.750,  5.000) = 2786 
    [ 5.000,  6.250) = 410 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     13.712 ms/op
     p(99.9990) =     14.732 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  8.542 ms/op
                 existUser·p0.9999: 14.045 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  6.071 ms/op
                 existUser·p0.9999: 12.629 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 11.634 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389174
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 190995 
    [ 2.500,  3.750) = 194628 
    [ 3.750,  5.000) = 2328 
    [ 5.000,  6.250) = 725 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      7.273 ms/op
     p(99.9900) =     13.095 ms/op
     p(99.9990) =     14.476 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  5.496 ms/op
                 getUser·p0.9999: 14.509 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  9.034 ms/op
                 getUser·p0.9999: 13.648 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  8.590 ms/op
                 getUser·p0.9999: 12.392 ms/op
                 getUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382707
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 188176 
    [ 2.500,  3.750) = 189221 
    [ 3.750,  5.000) = 4286 
    [ 5.000,  6.250) = 609 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      6.144 ms/op
     p(99.9900) =     13.693 ms/op
     p(99.9990) =     15.235 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.009 ms/op
Iteration   1: 3.094 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  10.038 ms/op
                 listUser·p0.9999: 11.671 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   2: 3.091 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.878 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.748 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 11.889 ms/op
                 listUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310108
  mean =      3.093 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 76745 
    [ 2.500,  3.750) = 188195 
    [ 3.750,  5.000) = 36841 
    [ 5.000,  6.250) = 6671 
    [ 6.250,  7.500) = 873 
    [ 7.500,  8.750) = 145 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 262 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     10.042 ms/op
     p(99.9900) =     11.845 ms/op
     p(99.9990) =     12.832 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.293 ± 0.828  ops/ms
ClientPb.existUser                       thrpt       3  12.943 ± 1.826  ops/ms
ClientPb.getUser                         thrpt       3  12.642 ± 0.220  ops/ms
ClientPb.listUser                        thrpt       3  10.547 ± 0.937  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.504   ms/op
ClientPb.existUser                        avgt       3   2.470 ± 0.295   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.296   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.211   ms/op
ClientPb.createUser                     sample  380965   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.892           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.712           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.844           ms/op
ClientPb.existUser                      sample  389174   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.899           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.273           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.095           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  382707   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.895           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.144           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.693           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.138           ms/op
ClientPb.listUser                       sample  310108   3.093 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.905           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.042           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.845           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.271           ms/op
