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
# Warmup Iteration   1: 2.496 ops/ms
# Warmup Iteration   2: 5.522 ops/ms
# Warmup Iteration   3: 9.192 ops/ms
Iteration   1: 10.036 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 9.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.003 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (9.983, 10.003, 10.036), stdev = 0.029
  CI (99.9%): [9.468, 10.537] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.580 ops/ms
# Warmup Iteration   2: 9.563 ops/ms
# Warmup Iteration   3: 10.167 ops/ms
Iteration   1: 10.106 ops/ms
Iteration   2: 10.316 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.332 ±(99.9%) 4.286 ops/ms [Average]
  (min, avg, max) = (10.106, 10.332, 10.575), stdev = 0.235
  CI (99.9%): [6.047, 14.618] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ops/ms
# Warmup Iteration   2: 9.235 ops/ms
# Warmup Iteration   3: 9.924 ops/ms
Iteration   1: 9.592 ops/ms
Iteration   2: 10.326 ops/ms
Iteration   3: 9.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.832 ±(99.9%) 7.819 ops/ms [Average]
  (min, avg, max) = (9.576, 9.832, 10.326), stdev = 0.429
  CI (99.9%): [2.013, 17.650] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ops/ms
# Warmup Iteration   2: 7.883 ops/ms
# Warmup Iteration   3: 8.299 ops/ms
Iteration   1: 8.539 ops/ms
Iteration   2: 8.449 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.401 ±(99.9%) 3.041 ops/ms [Average]
  (min, avg, max) = (8.216, 8.401, 8.539), stdev = 0.167
  CI (99.9%): [5.361, 11.442] (assumes normal distribution)


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
# Warmup Iteration   1: 8.452 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.004 ms/op
Iteration   1: 3.319 ±(99.9%) 0.003 ms/op
Iteration   2: 3.344 ±(99.9%) 0.007 ms/op
Iteration   3: 3.100 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.255 ±(99.9%) 2.445 ms/op [Average]
  (min, avg, max) = (3.100, 3.255, 3.344), stdev = 0.134
  CI (99.9%): [0.809, 5.700] (assumes normal distribution)


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
# Warmup Iteration   1: 6.626 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.005 ms/op
Iteration   1: 3.168 ±(99.9%) 0.006 ms/op
Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.109 ±(99.9%) 1.828 ms/op [Average]
  (min, avg, max) = (2.994, 3.109, 3.168), stdev = 0.100
  CI (99.9%): [1.282, 4.937] (assumes normal distribution)


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
# Warmup Iteration   1: 7.768 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.002 ms/op
Iteration   1: 3.122 ±(99.9%) 0.007 ms/op
Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
Iteration   3: 3.266 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.182 ±(99.9%) 1.371 ms/op [Average]
  (min, avg, max) = (3.122, 3.182, 3.266), stdev = 0.075
  CI (99.9%): [1.811, 4.554] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.054 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.008 ms/op
Iteration   1: 3.861 ±(99.9%) 0.005 ms/op
Iteration   2: 3.684 ±(99.9%) 0.009 ms/op
Iteration   3: 3.647 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.730 ±(99.9%) 2.083 ms/op [Average]
  (min, avg, max) = (3.647, 3.730, 3.861), stdev = 0.114
  CI (99.9%): [1.647, 5.814] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.382 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
Iteration   1: 3.217 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  9.396 ms/op
                 createUser·p0.9999: 20.875 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  18.896 ms/op
                 createUser·p0.9999: 22.300 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  13.661 ms/op
                 createUser·p0.9999: 25.695 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300471
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19823 
    [ 2.500,  5.000) = 275156 
    [ 5.000,  7.500) = 4690 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.246 ms/op
     p(99.9900) =     24.706 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 6.778 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.171 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  13.222 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  13.779 ms/op
                 existUser·p0.9999: 23.243 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   3: 3.059 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  17.911 ms/op
                 existUser·p0.9999: 21.973 ms/op
                 existUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304865
  mean =      3.147 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29098 
    [ 2.500,  5.000) = 269240 
    [ 5.000,  7.500) = 5569 
    [ 7.500, 10.000) = 372 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 198 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     17.671 ms/op
     p(99.9900) =     22.365 ms/op
     p(99.9990) =     23.818 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.790 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
Iteration   1: 3.274 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.618 ms/op
                 getUser·p0.999:  17.278 ms/op
                 getUser·p0.9999: 20.240 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  13.995 ms/op
                 getUser·p0.9999: 22.671 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  10.474 ms/op
                 getUser·p0.9999: 22.911 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297047
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18540 
    [ 2.500,  5.000) = 270944 
    [ 5.000,  7.500) = 6378 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.435 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 9.483 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.011 ms/op
Iteration   1: 3.774 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  14.843 ms/op
                 listUser·p0.9999: 20.055 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 3.824 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.909 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  12.916 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.548 ms/op

Iteration   3: 3.725 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 18.266 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254264
  mean =      3.774 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 246351 
    [ 5.000,  7.500) = 5965 
    [ 7.500, 10.000) = 1238 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     18.832 ms/op
     p(99.9990) =     20.373 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.003 ± 0.534  ops/ms
ClientPb.existUser                       thrpt       3  10.332 ± 4.286  ops/ms
ClientPb.getUser                         thrpt       3   9.832 ± 7.819  ops/ms
ClientPb.listUser                        thrpt       3   8.401 ± 3.041  ops/ms
ClientPb.createUser                       avgt       3   3.255 ± 2.445   ms/op
ClientPb.existUser                        avgt       3   3.109 ± 1.828   ms/op
ClientPb.getUser                          avgt       3   3.182 ± 1.371   ms/op
ClientPb.listUser                         avgt       3   3.730 ± 2.083   ms/op
ClientPb.createUser                     sample  300471   3.194 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.975           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.246           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.706           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.837           ms/op
ClientPb.existUser                      sample  304865   3.147 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.802           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.671           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.365           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.953           ms/op
ClientPb.getUser                        sample  297047   3.229 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.791           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.254           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.741           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.052           ms/op
ClientPb.listUser                       sample  254264   3.774 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.749           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.832           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.611           ms/op
