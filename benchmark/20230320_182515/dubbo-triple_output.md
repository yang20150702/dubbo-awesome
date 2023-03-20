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
# Warmup Iteration   1: 2.246 ops/ms
# Warmup Iteration   2: 5.867 ops/ms
# Warmup Iteration   3: 8.838 ops/ms
Iteration   1: 8.992 ops/ms
Iteration   2: 8.750 ops/ms
Iteration   3: 9.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.931 ±(99.9%) 2.913 ops/ms [Average]
  (min, avg, max) = (8.750, 8.931, 9.052), stdev = 0.160
  CI (99.9%): [6.018, 11.845] (assumes normal distribution)


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
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 9.225 ops/ms
# Warmup Iteration   3: 9.673 ops/ms
Iteration   1: 10.010 ops/ms
Iteration   2: 9.358 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.843 ±(99.9%) 7.789 ops/ms [Average]
  (min, avg, max) = (9.358, 9.843, 10.161), stdev = 0.427
  CI (99.9%): [2.054, 17.632] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ops/ms
# Warmup Iteration   2: 8.541 ops/ms
# Warmup Iteration   3: 9.419 ops/ms
Iteration   1: 9.259 ops/ms
Iteration   2: 9.764 ops/ms
Iteration   3: 9.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.519 ±(99.9%) 4.612 ops/ms [Average]
  (min, avg, max) = (9.259, 9.519, 9.764), stdev = 0.253
  CI (99.9%): [4.908, 14.131] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.947 ops/ms
# Warmup Iteration   2: 7.070 ops/ms
# Warmup Iteration   3: 8.054 ops/ms
Iteration   1: 8.206 ops/ms
Iteration   2: 8.294 ops/ms
Iteration   3: 8.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.265 ±(99.9%) 0.941 ops/ms [Average]
  (min, avg, max) = (8.206, 8.265, 8.296), stdev = 0.052
  CI (99.9%): [7.324, 9.207] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.684 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.003 ms/op
Iteration   1: 3.332 ±(99.9%) 0.007 ms/op
Iteration   2: 3.442 ±(99.9%) 0.006 ms/op
Iteration   3: 3.342 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.372 ±(99.9%) 1.104 ms/op [Average]
  (min, avg, max) = (3.332, 3.372, 3.442), stdev = 0.061
  CI (99.9%): [2.268, 4.476] (assumes normal distribution)


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
# Warmup Iteration   1: 7.565 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.005 ms/op
Iteration   1: 3.219 ±(99.9%) 0.006 ms/op
Iteration   2: 3.173 ±(99.9%) 0.009 ms/op
Iteration   3: 3.286 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.226 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (3.173, 3.226, 3.286), stdev = 0.057
  CI (99.9%): [2.185, 4.266] (assumes normal distribution)


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
# Warmup Iteration   1: 9.886 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.005 ms/op
Iteration   1: 3.363 ±(99.9%) 0.004 ms/op
Iteration   2: 3.486 ±(99.9%) 0.008 ms/op
Iteration   3: 3.373 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.407 ±(99.9%) 1.240 ms/op [Average]
  (min, avg, max) = (3.363, 3.407, 3.486), stdev = 0.068
  CI (99.9%): [2.167, 4.647] (assumes normal distribution)


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
# Warmup Iteration   1: 10.215 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.837 ±(99.9%) 0.012 ms/op
Iteration   2: 3.955 ±(99.9%) 0.003 ms/op
Iteration   3: 3.898 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.897 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.837, 3.897, 3.955), stdev = 0.059
  CI (99.9%): [2.818, 4.976] (assumes normal distribution)


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
# Warmup Iteration   1: 10.082 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.013 ms/op
Iteration   1: 3.537 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  20.457 ms/op
                 createUser·p0.9999: 23.559 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.341 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.351 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  22.223 ms/op
                 createUser·p0.9999: 27.178 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 3.342 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.401 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 32.450 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281788
  mean =      3.404 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5943 
    [ 2.500,  5.000) = 265545 
    [ 5.000,  7.500) = 9130 
    [ 7.500, 10.000) = 704 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     30.287 ms/op
     p(99.9990) =     33.343 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.508 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
Iteration   1: 3.289 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  16.683 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.329 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.077 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 37.487 ms/op
                 existUser·p1.00:   38.601 ms/op

Iteration   3: 3.389 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.416 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  24.325 ms/op
                 existUser·p0.9999: 27.361 ms/op
                 existUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287711
  mean =      3.335 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9228 
    [ 2.500,  5.000) = 271007 
    [ 5.000,  7.500) = 6254 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     38.543 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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
# Warmup Iteration   1: 10.571 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.012 ms/op
Iteration   1: 3.510 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.770 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  18.349 ms/op
                 getUser·p0.9999: 21.787 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.408 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  19.708 ms/op
                 getUser·p0.9999: 22.544 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  19.628 ms/op
                 getUser·p0.9999: 31.318 ms/op
                 getUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280740
  mean =      3.418 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7050 
    [ 2.500,  5.000) = 265459 
    [ 5.000,  7.500) = 7295 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     18.359 ms/op
     p(99.9900) =     29.712 ms/op
     p(99.9990) =     32.498 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 9.455 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.013 ms/op
Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 23.850 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 3.907 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.862 ms/op
                 listUser·p0.9999: 19.040 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.833 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.797 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246894
  mean =      3.889 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 239551 
    [ 5.000,  7.500) = 5265 
    [ 7.500, 10.000) = 1250 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     22.219 ms/op
     p(99.9990) =     25.235 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.931 ± 2.913  ops/ms
ClientPb.existUser                       thrpt       3   9.843 ± 7.789  ops/ms
ClientPb.getUser                         thrpt       3   9.519 ± 4.612  ops/ms
ClientPb.listUser                        thrpt       3   8.265 ± 0.941  ops/ms
ClientPb.createUser                       avgt       3   3.372 ± 1.104   ms/op
ClientPb.existUser                        avgt       3   3.226 ± 1.040   ms/op
ClientPb.getUser                          avgt       3   3.407 ± 1.240   ms/op
ClientPb.listUser                         avgt       3   3.897 ± 1.079   ms/op
ClientPb.createUser                     sample  281788   3.404 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.351           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.956           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.287           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  287711   3.335 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.416           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.108           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.045           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.601           ms/op
ClientPb.getUser                        sample  280740   3.418 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.102           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.359           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.712           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.456           ms/op
ClientPb.listUser                       sample  246894   3.889 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.161           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.219           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.592           ms/op
