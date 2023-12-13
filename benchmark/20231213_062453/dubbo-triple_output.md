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
# Warmup Iteration   1: 4.814 ops/ms
# Warmup Iteration   2: 12.108 ops/ms
# Warmup Iteration   3: 12.228 ops/ms
Iteration   1: 12.290 ops/ms
Iteration   2: 12.391 ops/ms
Iteration   3: 12.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.428 ±(99.9%) 2.912 ops/ms [Average]
  (min, avg, max) = (12.290, 12.428, 12.603), stdev = 0.160
  CI (99.9%): [9.516, 15.340] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.057 ops/ms
# Warmup Iteration   2: 12.740 ops/ms
# Warmup Iteration   3: 12.839 ops/ms
Iteration   1: 12.909 ops/ms
Iteration   2: 12.918 ops/ms
Iteration   3: 12.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.901 ±(99.9%) 0.390 ops/ms [Average]
  (min, avg, max) = (12.877, 12.901, 12.918), stdev = 0.021
  CI (99.9%): [12.511, 13.291] (assumes normal distribution)


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
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 12.491 ops/ms
# Warmup Iteration   3: 12.389 ops/ms
Iteration   1: 12.676 ops/ms
Iteration   2: 12.812 ops/ms
Iteration   3: 12.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.718 ±(99.9%) 1.478 ops/ms [Average]
  (min, avg, max) = (12.668, 12.718, 12.812), stdev = 0.081
  CI (99.9%): [11.241, 14.196] (assumes normal distribution)


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
# Warmup Iteration   1: 6.675 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 10.496 ops/ms
Iteration   1: 10.484 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.469 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (10.426, 10.469, 10.497), stdev = 0.038
  CI (99.9%): [9.777, 11.161] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.597 ±(99.9%) 0.004 ms/op
Iteration   2: 2.583 ±(99.9%) 0.005 ms/op
Iteration   3: 2.589 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.590 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (2.583, 2.590, 2.597), stdev = 0.007
  CI (99.9%): [2.461, 2.719] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.833 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.497 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.490, 2.497, 2.507), stdev = 0.009
  CI (99.9%): [2.338, 2.656] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.517 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (2.514, 2.517, 2.519), stdev = 0.003
  CI (99.9%): [2.468, 2.566] (assumes normal distribution)


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.004 ms/op
Iteration   2: 3.019 ±(99.9%) 0.004 ms/op
Iteration   3: 3.024 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.024 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (3.019, 3.024, 3.027), stdev = 0.004
  CI (99.9%): [2.942, 3.105] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.713 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.422 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  10.867 ms/op
                 createUser·p0.9999: 13.521 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  9.632 ms/op
                 createUser·p0.9999: 12.065 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  8.495 ms/op
                 createUser·p0.9999: 10.923 ms/op
                 createUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379241
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 181587 
    [ 2.500,  3.750) = 193444 
    [ 3.750,  5.000) = 3236 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.561 ms/op
     p(99.9900) =     12.781 ms/op
     p(99.9990) =     14.698 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.498 ms/op
                 existUser·p0.9999: 13.653 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  6.321 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   13.124 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  6.013 ms/op
                 existUser·p0.9999: 11.750 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387011
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 192393 
    [ 2.500,  3.750) = 191758 
    [ 3.750,  5.000) = 2172 
    [ 5.000,  6.250) = 247 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      6.177 ms/op
     p(99.9900) =     13.051 ms/op
     p(99.9990) =     14.064 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  11.894 ms/op
                 getUser·p0.9999: 14.041 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.101 ms/op
                 getUser·p0.999:  9.261 ms/op
                 getUser·p0.9999: 15.122 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  8.814 ms/op
                 getUser·p0.9999: 11.773 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376691
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 183342 
    [ 2.500,  3.750) = 188016 
    [ 3.750,  5.000) = 4099 
    [ 5.000,  6.250) = 707 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     15.622 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 4.662 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.806 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.669 ms/op
                 listUser·p0.9999: 11.820 ms/op
                 listUser·p1.00:   13.238 ms/op

Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.797 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  10.388 ms/op
                 listUser·p0.9999: 11.364 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   3: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.705 ms/op
                 listUser·p0.9999: 11.363 ms/op
                 listUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312475
  mean =      3.069 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 78560 
    [ 2.500,  3.750) = 190971 
    [ 3.750,  5.000) = 35528 
    [ 5.000,  6.250) = 6050 
    [ 6.250,  7.500) = 582 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 235 
    [10.000, 11.250) = 255 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     10.003 ms/op
     p(99.9900) =     11.481 ms/op
     p(99.9990) =     13.071 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.428 ± 2.912  ops/ms
ClientPb.existUser                       thrpt       3  12.901 ± 0.390  ops/ms
ClientPb.getUser                         thrpt       3  12.718 ± 1.478  ops/ms
ClientPb.listUser                        thrpt       3  10.469 ± 0.692  ops/ms
ClientPb.createUser                       avgt       3   2.590 ± 0.129   ms/op
ClientPb.existUser                        avgt       3   2.497 ± 0.159   ms/op
ClientPb.getUser                          avgt       3   2.517 ± 0.049   ms/op
ClientPb.listUser                         avgt       3   3.024 ± 0.082   ms/op
ClientPb.createUser                     sample  379241   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.422           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.561           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.781           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.581           ms/op
ClientPb.existUser                      sample  387011   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.177           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.615           ms/op
ClientPb.getUser                        sample  376691   2.546 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.753           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.946           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  312475   3.069 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.797           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.003           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.481           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.238           ms/op
