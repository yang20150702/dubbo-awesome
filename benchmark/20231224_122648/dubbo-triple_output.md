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
# Warmup Iteration   1: 4.209 ops/ms
# Warmup Iteration   2: 11.737 ops/ms
# Warmup Iteration   3: 12.292 ops/ms
Iteration   1: 12.543 ops/ms
Iteration   2: 12.473 ops/ms
Iteration   3: 12.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.491 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (12.456, 12.491, 12.543), stdev = 0.046
  CI (99.9%): [11.645, 13.336] (assumes normal distribution)


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
# Warmup Iteration   1: 7.960 ops/ms
# Warmup Iteration   2: 12.900 ops/ms
# Warmup Iteration   3: 12.949 ops/ms
Iteration   1: 13.012 ops/ms
Iteration   2: 13.052 ops/ms
Iteration   3: 12.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.989 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (12.902, 12.989, 13.052), stdev = 0.078
  CI (99.9%): [11.574, 14.403] (assumes normal distribution)


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
# Warmup Iteration   1: 7.104 ops/ms
# Warmup Iteration   2: 12.120 ops/ms
# Warmup Iteration   3: 12.378 ops/ms
Iteration   1: 12.385 ops/ms
Iteration   2: 12.416 ops/ms
Iteration   3: 12.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.425 ±(99.9%) 0.810 ops/ms [Average]
  (min, avg, max) = (12.385, 12.425, 12.473), stdev = 0.044
  CI (99.9%): [11.615, 13.234] (assumes normal distribution)


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
# Warmup Iteration   1: 6.485 ops/ms
# Warmup Iteration   2: 10.284 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.400 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (10.358, 10.400, 10.434), stdev = 0.039
  CI (99.9%): [9.693, 11.108] (assumes normal distribution)


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
Iteration   3: 2.572 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (2.519, 2.545, 2.572), stdev = 0.026
  CI (99.9%): [2.063, 3.027] (assumes normal distribution)


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.510 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.502, 2.510, 2.519), stdev = 0.009
  CI (99.9%): [2.349, 2.671] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.526 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.511, 2.526, 2.546), stdev = 0.018
  CI (99.9%): [2.191, 2.861] (assumes normal distribution)


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
Iteration   3: 3.050 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.037 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (3.024, 3.037, 3.050), stdev = 0.013
  CI (99.9%): [2.801, 3.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.587 ±(99.9%) 0.007 ms/op
Iteration   1: 2.557 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.944 ms/op
                 createUser·p0.9999: 14.500 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 14.175 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   3: 2.589 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  8.094 ms/op
                 createUser·p0.9999: 11.867 ms/op
                 createUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374086
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 177350 
    [ 2.500,  3.750) = 192794 
    [ 3.750,  5.000) = 3192 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.174 ms/op
     p(99.9900) =     14.116 ms/op
     p(99.9990) =     15.258 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  5.884 ms/op
                 existUser·p0.9999: 13.806 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.733 ms/op
                 existUser·p0.999:  7.608 ms/op
                 existUser·p0.9999: 15.719 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.732 ms/op
                 existUser·p0.999:  8.926 ms/op
                 existUser·p0.9999: 12.133 ms/op
                 existUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383712
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 187860 
    [ 2.500,  3.750) = 192172 
    [ 3.750,  5.000) = 2940 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      7.310 ms/op
     p(99.9900) =     14.189 ms/op
     p(99.9990) =     16.436 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  11.709 ms/op
                 getUser·p0.9999: 14.611 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  9.529 ms/op
                 getUser·p0.9999: 14.123 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 11.691 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374213
  mean =      2.563 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 180341 
    [ 2.500,  3.750) = 187842 
    [ 3.750,  5.000) = 4595 
    [ 5.000,  6.250) = 945 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =      8.549 ms/op
     p(99.9900) =     14.165 ms/op
     p(99.9990) =     15.524 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.942 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.009 ms/op
Iteration   1: 3.091 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.387 ms/op
                 listUser·p1.00:   13.320 ms/op

Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  10.584 ms/op
                 listUser·p0.9999: 14.790 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.712 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.486 ms/op
                 listUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312154
  mean =      3.073 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 77788 
    [ 2.500,  3.750) = 192818 
    [ 3.750,  5.000) = 34336 
    [ 5.000,  6.250) = 5743 
    [ 6.250,  7.500) = 702 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     16.720 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.491 ± 0.846  ops/ms
ClientPb.existUser                       thrpt       3  12.989 ± 1.415  ops/ms
ClientPb.getUser                         thrpt       3  12.425 ± 0.810  ops/ms
ClientPb.listUser                        thrpt       3  10.400 ± 0.708  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.482   ms/op
ClientPb.existUser                        avgt       3   2.510 ± 0.161   ms/op
ClientPb.getUser                          avgt       3   2.526 ± 0.335   ms/op
ClientPb.listUser                         avgt       3   3.037 ± 0.237   ms/op
ClientPb.createUser                     sample  374086   2.564 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.943           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.174           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.116           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.434           ms/op
ClientPb.existUser                      sample  383712   2.499 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.988           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.310           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.499           ms/op
ClientPb.getUser                        sample  374213   2.563 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.749           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.549           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.165           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.827           ms/op
ClientPb.listUser                       sample  312154   3.073 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.712           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.091           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.876           ms/op
