# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.989 ops/ms
# Warmup Iteration   2: 2.218 ops/ms
# Warmup Iteration   3: 5.101 ops/ms
Iteration   1: 5.291 ops/ms
Iteration   2: 5.578 ops/ms
Iteration   3: 5.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.510 ±(99.9%) 3.533 ops/ms [Average]
  (min, avg, max) = (5.291, 5.510, 5.660), stdev = 0.194
  CI (99.9%): [1.976, 9.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.624 ops/ms
# Warmup Iteration   2: 4.550 ops/ms
# Warmup Iteration   3: 5.526 ops/ms
Iteration   1: 5.811 ops/ms
Iteration   2: 5.700 ops/ms
Iteration   3: 5.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.767 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (5.700, 5.767, 5.811), stdev = 0.059
  CI (99.9%): [4.691, 6.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.534 ops/ms
# Warmup Iteration   2: 4.527 ops/ms
# Warmup Iteration   3: 5.368 ops/ms
Iteration   1: 5.299 ops/ms
Iteration   2: 5.486 ops/ms
Iteration   3: 5.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.442 ±(99.9%) 2.310 ops/ms [Average]
  (min, avg, max) = (5.299, 5.442, 5.540), stdev = 0.127
  CI (99.9%): [3.132, 7.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.456 ops/ms
# Warmup Iteration   2: 3.047 ops/ms
# Warmup Iteration   3: 4.458 ops/ms
Iteration   1: 4.490 ops/ms
Iteration   2: 4.773 ops/ms
Iteration   3: 4.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.658 ±(99.9%) 2.714 ops/ms [Average]
  (min, avg, max) = (4.490, 4.658, 4.773), stdev = 0.149
  CI (99.9%): [1.944, 7.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 19.885 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.346 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.078 ±(99.9%) 0.015 ms/op
Iteration   1: 6.100 ±(99.9%) 0.012 ms/op
Iteration   2: 5.883 ±(99.9%) 0.011 ms/op
Iteration   3: 5.751 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.911 ±(99.9%) 3.215 ms/op [Average]
  (min, avg, max) = (5.751, 5.911, 6.100), stdev = 0.176
  CI (99.9%): [2.697, 9.126] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 19.356 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.803 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.725 ±(99.9%) 0.007 ms/op
Iteration   1: 5.583 ±(99.9%) 0.007 ms/op
Iteration   2: 5.677 ±(99.9%) 0.009 ms/op
Iteration   3: 5.497 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.586 ±(99.9%) 1.643 ms/op [Average]
  (min, avg, max) = (5.497, 5.586, 5.677), stdev = 0.090
  CI (99.9%): [3.943, 7.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 20.053 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.399 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.741 ±(99.9%) 0.022 ms/op
Iteration   1: 5.867 ±(99.9%) 0.009 ms/op
Iteration   2: 6.120 ±(99.9%) 0.010 ms/op
Iteration   3: 5.957 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.981 ±(99.9%) 2.347 ms/op [Average]
  (min, avg, max) = (5.867, 5.981, 6.120), stdev = 0.129
  CI (99.9%): [3.635, 8.328] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 20.988 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 8.870 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.832 ±(99.9%) 0.016 ms/op
Iteration   1: 6.706 ±(99.9%) 0.014 ms/op
Iteration   2: 6.940 ±(99.9%) 0.016 ms/op
Iteration   3: 6.829 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.825 ±(99.9%) 2.137 ms/op [Average]
  (min, avg, max) = (6.706, 6.825, 6.940), stdev = 0.117
  CI (99.9%): [4.688, 8.962] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 20.706 ±(99.9%) 0.348 ms/op
# Warmup Iteration   2: 8.049 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.332 ±(99.9%) 0.033 ms/op
Iteration   1: 5.957 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.433 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   7.881 ms/op
                 createUser·p0.95:   9.110 ms/op
                 createUser·p0.99:   12.350 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 29.729 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   2: 5.761 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.291 ms/op
                 createUser·p0.95:   8.503 ms/op
                 createUser·p0.99:   11.649 ms/op
                 createUser·p0.999:  27.558 ms/op
                 createUser·p0.9999: 31.556 ms/op
                 createUser·p1.00:   36.635 ms/op

Iteration   3: 5.886 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.447 ms/op
                 createUser·p0.95:   8.700 ms/op
                 createUser·p0.99:   12.595 ms/op
                 createUser·p0.999:  32.178 ms/op
                 createUser·p0.9999: 35.145 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163568
  mean =      5.867 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 43187 
    [ 5.000,  7.500) = 103863 
    [ 7.500, 10.000) = 12218 
    [10.000, 12.500) = 2823 
    [12.500, 15.000) = 889 
    [15.000, 17.500) = 285 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 41 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.512 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     25.551 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     36.778 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.237 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 7.608 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.799 ±(99.9%) 0.024 ms/op
Iteration   1: 5.665 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.465 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.503 ms/op
                 existUser·p0.99:   11.846 ms/op
                 existUser·p0.999:  26.909 ms/op
                 existUser·p0.9999: 33.733 ms/op
                 existUser·p1.00:   34.144 ms/op

Iteration   2: 5.564 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.249 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   7.029 ms/op
                 existUser·p0.95:   8.077 ms/op
                 existUser·p0.99:   11.256 ms/op
                 existUser·p0.999:  29.243 ms/op
                 existUser·p0.9999: 32.514 ms/op
                 existUser·p1.00:   34.800 ms/op

Iteration   3: 5.788 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.494 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.561 ms/op
                 existUser·p0.95:   8.798 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  17.242 ms/op
                 existUser·p0.9999: 31.995 ms/op
                 existUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169230
  mean =      5.671 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 60566 
    [ 5.000,  7.500) = 93952 
    [ 7.500, 10.000) = 11069 
    [10.000, 12.500) = 2574 
    [12.500, 15.000) = 614 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      7.266 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     19.358 ms/op
     p(99.9900) =     32.755 ms/op
     p(99.9990) =     34.618 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.626 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 7.524 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.888 ±(99.9%) 0.022 ms/op
Iteration   1: 6.375 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   1.886 ms/op
                 getUser·p0.50:   5.792 ms/op
                 getUser·p0.90:   8.487 ms/op
                 getUser·p0.95:   9.945 ms/op
                 getUser·p0.99:   15.848 ms/op
                 getUser·p0.999:  27.744 ms/op
                 getUser·p0.9999: 35.384 ms/op
                 getUser·p1.00:   37.093 ms/op

Iteration   2: 5.926 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.560 ms/op
                 getUser·p0.50:   5.464 ms/op
                 getUser·p0.90:   7.684 ms/op
                 getUser·p0.95:   8.864 ms/op
                 getUser·p0.99:   11.977 ms/op
                 getUser·p0.999:  31.655 ms/op
                 getUser·p0.9999: 34.970 ms/op
                 getUser·p1.00:   35.586 ms/op

Iteration   3: 6.193 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.753 ms/op
                 getUser·p0.50:   5.767 ms/op
                 getUser·p0.90:   8.135 ms/op
                 getUser·p0.95:   9.437 ms/op
                 getUser·p0.99:   12.534 ms/op
                 getUser·p0.999:  17.591 ms/op
                 getUser·p0.9999: 35.707 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155694
  mean =      6.159 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 32682 
    [ 5.000,  7.500) = 101760 
    [ 7.500, 10.000) = 15594 
    [10.000, 12.500) = 3514 
    [12.500, 15.000) = 1254 
    [15.000, 17.500) = 445 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 46 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      5.669 ms/op
     p(90.0000) =      8.077 ms/op
     p(95.0000) =      9.421 ms/op
     p(99.0000) =     13.386 ms/op
     p(99.9000) =     27.525 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     37.020 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.935 ±(99.9%) 0.406 ms/op
# Warmup Iteration   2: 9.062 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 7.131 ±(99.9%) 0.033 ms/op
Iteration   1: 6.947 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   9.044 ms/op
                 listUser·p0.95:   10.600 ms/op
                 listUser·p0.99:   13.749 ms/op
                 listUser·p0.999:  25.455 ms/op
                 listUser·p0.9999: 28.337 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 6.986 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   6.529 ms/op
                 listUser·p0.90:   8.880 ms/op
                 listUser·p0.95:   10.174 ms/op
                 listUser·p0.99:   13.533 ms/op
                 listUser·p0.999:  28.300 ms/op
                 listUser·p0.9999: 31.789 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 7.011 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.314 ms/op
                 listUser·p0.50:   6.447 ms/op
                 listUser·p0.90:   9.044 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   14.205 ms/op
                 listUser·p0.999:  29.021 ms/op
                 listUser·p0.9999: 33.266 ms/op
                 listUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137532
  mean =      6.981 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2830 
    [ 5.000,  7.500) = 101309 
    [ 7.500, 10.000) = 25018 
    [10.000, 12.500) = 5910 
    [12.500, 15.000) = 1505 
    [15.000, 17.500) = 481 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      6.472 ms/op
     p(90.0000) =      8.978 ms/op
     p(95.0000) =     10.404 ms/op
     p(99.0000) =     13.828 ms/op
     p(99.9000) =     27.492 ms/op
     p(99.9900) =     32.620 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.510 ± 3.533  ops/ms
ClientPb.existUser                       thrpt       3   5.767 ± 1.076  ops/ms
ClientPb.getUser                         thrpt       3   5.442 ± 2.310  ops/ms
ClientPb.listUser                        thrpt       3   4.658 ± 2.714  ops/ms
ClientPb.createUser                       avgt       3   5.911 ± 3.215   ms/op
ClientPb.existUser                        avgt       3   5.586 ± 1.643   ms/op
ClientPb.getUser                          avgt       3   5.981 ± 2.347   ms/op
ClientPb.listUser                         avgt       3   6.825 ± 2.137   ms/op
ClientPb.createUser                     sample  163568   5.867 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.812           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.512           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.831           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.141           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.551           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.603           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  169230   5.671 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.465           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.266           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.487           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.518           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.358           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.755           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.800           ms/op
ClientPb.getUser                        sample  155694   6.159 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.560           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.077           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.421           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.386           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.525           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.521           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.093           ms/op
ClientPb.listUser                       sample  137532   6.981 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.367           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.472           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.978           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.404           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.828           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.492           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.620           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.734           ms/op
