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
# Warmup Iteration   1: 4.825 ops/ms
# Warmup Iteration   2: 12.108 ops/ms
# Warmup Iteration   3: 12.363 ops/ms
Iteration   1: 12.653 ops/ms
Iteration   2: 12.655 ops/ms
Iteration   3: 12.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.632 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (12.589, 12.632, 12.655), stdev = 0.037
  CI (99.9%): [11.950, 13.315] (assumes normal distribution)


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
# Warmup Iteration   1: 8.082 ops/ms
# Warmup Iteration   2: 12.733 ops/ms
# Warmup Iteration   3: 13.083 ops/ms
Iteration   1: 12.960 ops/ms
Iteration   2: 13.187 ops/ms
Iteration   3: 12.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.035 ±(99.9%) 2.397 ops/ms [Average]
  (min, avg, max) = (12.960, 13.035, 13.187), stdev = 0.131
  CI (99.9%): [10.639, 15.432] (assumes normal distribution)


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
# Warmup Iteration   1: 7.663 ops/ms
# Warmup Iteration   2: 12.401 ops/ms
# Warmup Iteration   3: 12.834 ops/ms
Iteration   1: 12.926 ops/ms
Iteration   2: 12.929 ops/ms
Iteration   3: 12.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.904 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (12.857, 12.904, 12.929), stdev = 0.040
  CI (99.9%): [12.167, 13.641] (assumes normal distribution)


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
# Warmup Iteration   1: 6.829 ops/ms
# Warmup Iteration   2: 10.516 ops/ms
# Warmup Iteration   3: 10.809 ops/ms
Iteration   1: 10.807 ops/ms
Iteration   2: 10.729 ops/ms
Iteration   3: 10.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.758 ±(99.9%) 0.780 ops/ms [Average]
  (min, avg, max) = (10.729, 10.758, 10.807), stdev = 0.043
  CI (99.9%): [9.978, 11.538] (assumes normal distribution)


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.489 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (2.473, 2.489, 2.519), stdev = 0.026
  CI (99.9%): [2.021, 2.957] (assumes normal distribution)


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.400 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
Iteration   3: 2.412 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.413 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.405, 2.413, 2.422), stdev = 0.008
  CI (99.9%): [2.263, 2.563] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.992 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.520 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (2.516, 2.520, 2.528), stdev = 0.007
  CI (99.9%): [2.395, 2.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.827 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.004 ms/op
Iteration   1: 3.011 ±(99.9%) 0.005 ms/op
Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
Iteration   3: 2.978 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.998 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.978, 2.998, 3.011), stdev = 0.018
  CI (99.9%): [2.676, 3.320] (assumes normal distribution)


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  10.501 ms/op
                 createUser·p0.9999: 13.615 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  9.660 ms/op
                 createUser·p0.9999: 12.812 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  10.007 ms/op
                 createUser·p0.9999: 11.530 ms/op
                 createUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382943
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 184635 
    [ 2.500,  3.750) = 194563 
    [ 3.750,  5.000) = 2940 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     13.397 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  6.224 ms/op
                 existUser·p0.9999: 14.087 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.539 ms/op
                 existUser·p0.9999: 14.234 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  8.024 ms/op
                 existUser·p0.9999: 12.042 ms/op
                 existUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392432
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 194714 
    [ 2.500,  3.750) = 194279 
    [ 3.750,  5.000) = 2595 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      7.875 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     14.519 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  11.712 ms/op
                 getUser·p0.9999: 13.586 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  5.812 ms/op
                 getUser·p0.9999: 12.923 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 12.112 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380723
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 186677 
    [ 2.500,  3.750) = 189209 
    [ 3.750,  5.000) = 3692 
    [ 5.000,  6.250) = 707 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      6.122 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.040 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 4.726 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.555 ms/op
                 listUser·p0.9999: 11.358 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   2: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 11.597 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.822 ms/op
                 listUser·p0.9999: 11.198 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316681
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 88475 
    [ 2.500,  3.750) = 188626 
    [ 3.750,  5.000) = 32469 
    [ 5.000,  6.250) = 5779 
    [ 6.250,  7.500) = 553 
    [ 7.500,  8.750) = 165 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 228 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     11.409 ms/op
     p(99.9990) =     12.340 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.632 ± 0.683  ops/ms
ClientPb.existUser                       thrpt       3  13.035 ± 2.397  ops/ms
ClientPb.getUser                         thrpt       3  12.904 ± 0.737  ops/ms
ClientPb.listUser                        thrpt       3  10.758 ± 0.780  ops/ms
ClientPb.createUser                       avgt       3   2.489 ± 0.468   ms/op
ClientPb.existUser                        avgt       3   2.413 ± 0.150   ms/op
ClientPb.getUser                          avgt       3   2.520 ± 0.125   ms/op
ClientPb.listUser                         avgt       3   2.998 ± 0.322   ms/op
ClientPb.createUser                     sample  382943   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.508           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.748           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.397           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  392432   2.444 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.736           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.875           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  380723   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.754           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.122           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.221           ms/op
ClientPb.listUser                       sample  316681   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.805           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.830           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.409           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.829           ms/op
