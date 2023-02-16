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
# Warmup Iteration   1: 1.613 ops/ms
# Warmup Iteration   2: 4.321 ops/ms
# Warmup Iteration   3: 7.488 ops/ms
Iteration   1: 7.504 ops/ms
Iteration   2: 8.588 ops/ms
Iteration   3: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.120 ±(99.9%) 10.161 ops/ms [Average]
  (min, avg, max) = (7.504, 8.120, 8.588), stdev = 0.557
  CI (99.9%): [≈ 0, 18.280] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.555 ops/ms
# Warmup Iteration   2: 7.364 ops/ms
# Warmup Iteration   3: 8.053 ops/ms
Iteration   1: 8.673 ops/ms
Iteration   2: 8.632 ops/ms
Iteration   3: 8.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.652 ±(99.9%) 0.373 ops/ms [Average]
  (min, avg, max) = (8.632, 8.652, 8.673), stdev = 0.020
  CI (99.9%): [8.279, 9.026] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.301 ops/ms
# Warmup Iteration   2: 6.866 ops/ms
# Warmup Iteration   3: 8.432 ops/ms
Iteration   1: 8.211 ops/ms
Iteration   2: 8.270 ops/ms
Iteration   3: 8.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.349 ±(99.9%) 3.473 ops/ms [Average]
  (min, avg, max) = (8.211, 8.349, 8.566), stdev = 0.190
  CI (99.9%): [4.876, 11.822] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.328 ops/ms
# Warmup Iteration   2: 6.150 ops/ms
# Warmup Iteration   3: 7.154 ops/ms
Iteration   1: 7.113 ops/ms
Iteration   2: 7.156 ops/ms
Iteration   3: 7.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.137 ±(99.9%) 0.397 ops/ms [Average]
  (min, avg, max) = (7.113, 7.137, 7.156), stdev = 0.022
  CI (99.9%): [6.740, 7.533] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.697 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.005 ms/op
Iteration   1: 3.469 ±(99.9%) 0.009 ms/op
Iteration   2: 3.478 ±(99.9%) 0.007 ms/op
Iteration   3: 3.412 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.453 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (3.412, 3.453, 3.478), stdev = 0.036
  CI (99.9%): [2.800, 4.106] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.753 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.008 ms/op
Iteration   1: 3.313 ±(99.9%) 0.009 ms/op
Iteration   2: 3.330 ±(99.9%) 0.011 ms/op
Iteration   3: 3.304 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.316 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (3.304, 3.316, 3.330), stdev = 0.013
  CI (99.9%): [3.074, 3.557] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.165 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.004 ms/op
Iteration   1: 3.835 ±(99.9%) 0.010 ms/op
Iteration   2: 3.694 ±(99.9%) 0.004 ms/op
Iteration   3: 3.638 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.722 ±(99.9%) 1.852 ms/op [Average]
  (min, avg, max) = (3.638, 3.722, 3.835), stdev = 0.102
  CI (99.9%): [1.870, 5.574] (assumes normal distribution)


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
# Warmup Iteration   1: 12.167 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.982 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.480 ±(99.9%) 0.008 ms/op
Iteration   1: 4.439 ±(99.9%) 0.008 ms/op
Iteration   2: 4.310 ±(99.9%) 0.013 ms/op
Iteration   3: 4.038 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.262 ±(99.9%) 3.735 ms/op [Average]
  (min, avg, max) = (4.038, 4.262, 4.439), stdev = 0.205
  CI (99.9%): [0.527, 7.997] (assumes normal distribution)


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
# Warmup Iteration   1: 10.717 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.521 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.017 ms/op
Iteration   1: 3.630 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  11.838 ms/op
                 createUser·p0.9999: 24.680 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 3.762 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.356 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  23.946 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   3: 3.904 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   7.774 ms/op
                 createUser·p0.999:  25.602 ms/op
                 createUser·p0.9999: 40.096 ms/op
                 createUser·p1.00:   41.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 255339
  mean =      3.762 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 242544 
    [ 5.000, 10.000) = 12112 
    [10.000, 15.000) = 415 
    [15.000, 20.000) = 15 
    [20.000, 25.000) = 106 
    [25.000, 30.000) = 115 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     38.273 ms/op
     p(99.9990) =     40.618 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


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
# Warmup Iteration   1: 10.443 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.011 ms/op
Iteration   1: 3.382 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  18.381 ms/op
                 existUser·p0.9999: 24.448 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   2: 3.616 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  14.061 ms/op
                 existUser·p0.9999: 27.470 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.599 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  23.003 ms/op
                 existUser·p0.9999: 30.223 ms/op
                 existUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271829
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2994 
    [ 2.500,  5.000) = 261471 
    [ 5.000,  7.500) = 6142 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.043 ms/op
     p(99.9000) =     14.833 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     30.418 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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
# Warmup Iteration   1: 10.171 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.011 ms/op
Iteration   1: 3.780 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   8.135 ms/op
                 getUser·p0.999:  21.732 ms/op
                 getUser·p0.9999: 24.593 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 3.584 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  24.462 ms/op
                 getUser·p0.9999: 30.116 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 3.754 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  13.563 ms/op
                 getUser·p0.9999: 31.261 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 259231
  mean =      3.704 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3699 
    [ 2.500,  5.000) = 244083 
    [ 5.000,  7.500) = 9247 
    [ 7.500, 10.000) = 1539 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.198 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     32.303 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 12.075 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.016 ms/op
Iteration   1: 3.975 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  22.564 ms/op
                 listUser·p0.9999: 26.313 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 3.937 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.005 ms/op
                 listUser·p0.999:  16.543 ms/op
                 listUser·p0.9999: 18.899 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.093 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 22.452 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239929
  mean =      4.001 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 246 
    [ 2.500,  5.000) = 231277 
    [ 5.000,  7.500) = 6380 
    [ 7.500, 10.000) = 1125 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 250 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     26.929 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.120 ± 10.161  ops/ms
ClientPb.existUser                       thrpt       3   8.652 ±  0.373  ops/ms
ClientPb.getUser                         thrpt       3   8.349 ±  3.473  ops/ms
ClientPb.listUser                        thrpt       3   7.137 ±  0.397  ops/ms
ClientPb.createUser                       avgt       3   3.453 ±  0.653   ms/op
ClientPb.existUser                        avgt       3   3.316 ±  0.242   ms/op
ClientPb.getUser                          avgt       3   3.722 ±  1.852   ms/op
ClientPb.listUser                         avgt       3   4.262 ±  3.735   ms/op
ClientPb.createUser                     sample  255339   3.762 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.356            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.629            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.415            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.816            ms/op
ClientPb.createUser:createUser·p0.999   sample          19.530            ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.273            ms/op
ClientPb.createUser:createUser·p1.00    sample          41.288            ms/op
ClientPb.existUser                      sample  271829   3.529 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.536            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.453            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.953            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.325            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.043            ms/op
ClientPb.existUser:existUser·p0.999     sample          14.833            ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.901            ms/op
ClientPb.existUser:existUser·p1.00      sample          30.966            ms/op
ClientPb.getUser                        sample  259231   3.704 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.592            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.301            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.817            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.198            ms/op
ClientPb.getUser:getUser·p0.999         sample          21.135            ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.507            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342            ms/op
ClientPb.listUser                       sample  239929   4.001 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.399            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266            ms/op
ClientPb.listUser:listUser·p0.999       sample          17.105            ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.871            ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034            ms/op
