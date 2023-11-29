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
# Warmup Iteration   1: 4.606 ops/ms
# Warmup Iteration   2: 11.898 ops/ms
# Warmup Iteration   3: 12.473 ops/ms
Iteration   1: 12.566 ops/ms
Iteration   2: 12.602 ops/ms
Iteration   3: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.624 ±(99.9%) 1.325 ops/ms [Average]
  (min, avg, max) = (12.566, 12.624, 12.706), stdev = 0.073
  CI (99.9%): [11.299, 13.950] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 8.086 ops/ms
# Warmup Iteration   2: 12.888 ops/ms
# Warmup Iteration   3: 12.760 ops/ms
Iteration   1: 13.047 ops/ms
Iteration   2: 12.984 ops/ms
Iteration   3: 12.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.969 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (12.874, 12.969, 13.047), stdev = 0.088
  CI (99.9%): [11.372, 14.565] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.678 ops/ms
# Warmup Iteration   2: 12.592 ops/ms
# Warmup Iteration   3: 12.691 ops/ms
Iteration   1: 12.896 ops/ms
Iteration   2: 12.728 ops/ms
Iteration   3: 12.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.806 ±(99.9%) 1.548 ops/ms [Average]
  (min, avg, max) = (12.728, 12.806, 12.896), stdev = 0.085
  CI (99.9%): [11.258, 14.354] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.260 ops/ms
# Warmup Iteration   2: 10.513 ops/ms
# Warmup Iteration   3: 10.524 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.630 ±(99.9%) 1.982 ops/ms [Average]
  (min, avg, max) = (10.505, 10.630, 10.703), stdev = 0.109
  CI (99.9%): [8.648, 12.612] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (2.509, 2.530, 2.559), stdev = 0.026
  CI (99.9%): [2.048, 3.011] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.003 ms/op
Iteration   2: 2.452 ±(99.9%) 0.003 ms/op
Iteration   3: 2.462 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.452, 2.468, 2.490), stdev = 0.020
  CI (99.9%): [2.108, 2.828] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
Iteration   1: 2.544 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.537 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.527, 2.537, 2.544), stdev = 0.009
  CI (99.9%): [2.365, 2.710] (assumes normal distribution)


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
Iteration   2: 2.984 ±(99.9%) 0.007 ms/op
Iteration   3: 2.981 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.986 ±(99.9%) 0.095 ms/op [Average]
  (min, avg, max) = (2.981, 2.986, 2.991), stdev = 0.005
  CI (99.9%): [2.891, 3.081] (assumes normal distribution)


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  12.543 ms/op
                 createUser·p0.9999: 14.680 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.792 ms/op
                 createUser·p0.999:  10.831 ms/op
                 createUser·p0.9999: 13.325 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  9.110 ms/op
                 createUser·p0.9999: 10.838 ms/op
                 createUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378653
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 182484 
    [ 2.500,  3.750) = 190982 
    [ 3.750,  5.000) = 4127 
    [ 5.000,  6.250) = 484 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      9.569 ms/op
     p(99.9900) =     14.013 ms/op
     p(99.9990) =     14.847 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  6.826 ms/op
                 existUser·p0.9999: 14.205 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  5.981 ms/op
                 existUser·p0.9999: 13.481 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  8.025 ms/op
                 existUser·p0.9999: 12.665 ms/op
                 existUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389760
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 193124 
    [ 2.500,  3.750) = 192254 
    [ 3.750,  5.000) = 3387 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  12.763 ms/op
                 getUser·p0.9999: 14.222 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.047 ms/op
                 getUser·p0.999:  10.125 ms/op
                 getUser·p0.9999: 16.679 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  7.417 ms/op
                 getUser·p0.9999: 12.775 ms/op
                 getUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383000
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 189675 
    [ 2.500,  3.750) = 188192 
    [ 3.750,  5.000) = 3876 
    [ 5.000,  6.250) = 731 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 127 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     15.773 ms/op
     p(99.9990) =     16.952 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.009 ms/op
Iteration   1: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.033 ms/op
                 listUser·p0.9999: 11.398 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  10.154 ms/op
                 listUser·p0.9999: 11.044 ms/op
                 listUser·p1.00:   11.583 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.518 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 12.313 ms/op
                 listUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320442
  mean =      2.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 98189 
    [ 2.500,  3.750) = 184128 
    [ 3.750,  5.000) = 30376 
    [ 5.000,  6.250) = 6202 
    [ 6.250,  7.500) = 738 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 191 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     11.550 ms/op
     p(99.9990) =     12.940 ms/op
     p(99.9999) =     13.025 ms/op
    p(100.0000) =     13.025 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.624 ± 1.325  ops/ms
ClientPb.existUser                       thrpt       3  12.969 ± 1.597  ops/ms
ClientPb.getUser                         thrpt       3  12.806 ± 1.548  ops/ms
ClientPb.listUser                        thrpt       3  10.630 ± 1.982  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.482   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.360   ms/op
ClientPb.getUser                          avgt       3   2.537 ± 0.172   ms/op
ClientPb.listUser                         avgt       3   2.986 ± 0.095   ms/op
ClientPb.createUser                     sample  378653   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.677           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.569           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.013           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  389760   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.933           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.636           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.008           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.417           ms/op
ClientPb.getUser                        sample  383000   2.504 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.926           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.355           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.773           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.138           ms/op
ClientPb.listUser                       sample  320442   2.993 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.550           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.025           ms/op
