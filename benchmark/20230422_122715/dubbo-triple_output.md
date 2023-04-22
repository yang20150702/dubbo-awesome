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
# Warmup Iteration   1: 2.106 ops/ms
# Warmup Iteration   2: 5.287 ops/ms
# Warmup Iteration   3: 8.993 ops/ms
Iteration   1: 9.024 ops/ms
Iteration   2: 9.129 ops/ms
Iteration   3: 9.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.092 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (9.024, 9.092, 9.129), stdev = 0.058
  CI (99.9%): [8.026, 10.158] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.157 ops/ms
# Warmup Iteration   2: 8.911 ops/ms
# Warmup Iteration   3: 9.364 ops/ms
Iteration   1: 9.673 ops/ms
Iteration   2: 10.148 ops/ms
Iteration   3: 9.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.840 ±(99.9%) 4.876 ops/ms [Average]
  (min, avg, max) = (9.673, 9.840, 10.148), stdev = 0.267
  CI (99.9%): [4.964, 14.716] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.001 ops/ms
# Warmup Iteration   2: 7.535 ops/ms
# Warmup Iteration   3: 8.907 ops/ms
Iteration   1: 9.257 ops/ms
Iteration   2: 9.786 ops/ms
Iteration   3: 9.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.508 ±(99.9%) 4.838 ops/ms [Average]
  (min, avg, max) = (9.257, 9.508, 9.786), stdev = 0.265
  CI (99.9%): [4.671, 14.346] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.850 ops/ms
# Warmup Iteration   2: 7.379 ops/ms
# Warmup Iteration   3: 7.792 ops/ms
Iteration   1: 8.135 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.067 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (7.909, 8.067, 8.157), stdev = 0.137
  CI (99.9%): [5.561, 10.573] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.001 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.006 ms/op
Iteration   1: 3.283 ±(99.9%) 0.011 ms/op
Iteration   2: 3.395 ±(99.9%) 0.009 ms/op
Iteration   3: 3.466 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.381 ±(99.9%) 1.684 ms/op [Average]
  (min, avg, max) = (3.283, 3.381, 3.466), stdev = 0.092
  CI (99.9%): [1.698, 5.065] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.457 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.005 ms/op
Iteration   1: 3.315 ±(99.9%) 0.007 ms/op
Iteration   2: 3.256 ±(99.9%) 0.010 ms/op
Iteration   3: 3.279 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.283 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.256, 3.283, 3.315), stdev = 0.029
  CI (99.9%): [2.747, 3.820] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.853 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.007 ms/op
Iteration   1: 3.384 ±(99.9%) 0.003 ms/op
Iteration   2: 3.408 ±(99.9%) 0.012 ms/op
Iteration   3: 3.363 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.385 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.363, 3.385, 3.408), stdev = 0.022
  CI (99.9%): [2.976, 3.794] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.662 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.375 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
Iteration   1: 3.958 ±(99.9%) 0.013 ms/op
Iteration   2: 4.009 ±(99.9%) 0.012 ms/op
Iteration   3: 3.971 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.980 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (3.958, 3.980, 4.009), stdev = 0.027
  CI (99.9%): [3.495, 4.464] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.111 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.011 ms/op
Iteration   1: 3.509 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  19.134 ms/op
                 createUser·p0.9999: 22.770 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.481 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.765 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  22.316 ms/op
                 createUser·p0.9999: 24.576 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  14.205 ms/op
                 createUser·p0.9999: 24.766 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275207
  mean =      3.489 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10486 
    [ 2.500,  5.000) = 257083 
    [ 5.000,  7.500) = 6773 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     14.595 ms/op
     p(99.9900) =     24.559 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.645 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
Iteration   1: 3.222 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  8.280 ms/op
                 existUser·p0.9999: 23.661 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  10.236 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.395 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.041 ms/op
                 existUser·p0.999:  16.646 ms/op
                 existUser·p0.9999: 28.443 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291676
  mean =      3.291 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16071 
    [ 2.500,  5.000) = 271682 
    [ 5.000,  7.500) = 3308 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     26.471 ms/op
     p(99.9990) =     28.841 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.187 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.010 ms/op
Iteration   1: 3.436 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  21.326 ms/op
                 getUser·p0.9999: 27.570 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   2: 3.341 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 24.688 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  16.488 ms/op
                 getUser·p0.9999: 23.779 ms/op
                 getUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283518
  mean =      3.384 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5256 
    [ 2.500,  5.000) = 271377 
    [ 5.000,  7.500) = 5413 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     27.978 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.767 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.014 ms/op
Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  18.459 ms/op
                 listUser·p0.9999: 28.185 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   2: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 3.932 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.137 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239890
  mean =      4.001 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 230509 
    [ 5.000,  7.500) = 7367 
    [ 7.500, 10.000) = 1142 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     28.711 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.092 ± 1.066  ops/ms
ClientPb.existUser                       thrpt       3   9.840 ± 4.876  ops/ms
ClientPb.getUser                         thrpt       3   9.508 ± 4.838  ops/ms
ClientPb.listUser                        thrpt       3   8.067 ± 2.506  ops/ms
ClientPb.createUser                       avgt       3   3.381 ± 1.684   ms/op
ClientPb.existUser                        avgt       3   3.283 ± 0.536   ms/op
ClientPb.getUser                          avgt       3   3.385 ± 0.409   ms/op
ClientPb.listUser                         avgt       3   3.980 ± 0.485   ms/op
ClientPb.createUser                     sample  275207   3.489 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.946           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.595           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.559           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.051           ms/op
ClientPb.existUser                      sample  291676   3.291 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.229           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.240           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.471           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.196           ms/op
ClientPb.getUser                        sample  283518   3.384 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.090           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.219           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.657           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.180           ms/op
ClientPb.listUser                       sample  239890   4.001 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.604           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.039           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.706           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.360           ms/op
