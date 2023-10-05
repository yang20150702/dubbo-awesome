# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.899 ops/ms
# Warmup Iteration   2: 5.515 ops/ms
# Warmup Iteration   3: 8.288 ops/ms
Iteration   1: 9.079 ops/ms
Iteration   2: 8.739 ops/ms
Iteration   3: 9.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.964 ±(99.9%) 3.562 ops/ms [Average]
  (min, avg, max) = (8.739, 8.964, 9.079), stdev = 0.195
  CI (99.9%): [5.403, 12.526] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 8.224 ops/ms
# Warmup Iteration   3: 9.389 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.400 ops/ms
Iteration   3: 9.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.329 ±(99.9%) 1.127 ops/ms [Average]
  (min, avg, max) = (9.291, 9.329, 9.400), stdev = 0.062
  CI (99.9%): [8.202, 10.456] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.574 ops/ms
# Warmup Iteration   2: 8.086 ops/ms
# Warmup Iteration   3: 8.762 ops/ms
Iteration   1: 8.568 ops/ms
Iteration   2: 8.678 ops/ms
Iteration   3: 9.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.798 ±(99.9%) 5.619 ops/ms [Average]
  (min, avg, max) = (8.568, 8.798, 9.148), stdev = 0.308
  CI (99.9%): [3.179, 14.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.294 ops/ms
# Warmup Iteration   2: 6.627 ops/ms
# Warmup Iteration   3: 7.471 ops/ms
Iteration   1: 7.461 ops/ms
Iteration   2: 7.391 ops/ms
Iteration   3: 7.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.524 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (7.391, 7.524, 7.720), stdev = 0.173
  CI (99.9%): [4.366, 10.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.665 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.004 ms/op
Iteration   1: 3.661 ±(99.9%) 0.005 ms/op
Iteration   2: 3.577 ±(99.9%) 0.004 ms/op
Iteration   3: 3.479 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.572 ±(99.9%) 1.658 ms/op [Average]
  (min, avg, max) = (3.479, 3.572, 3.661), stdev = 0.091
  CI (99.9%): [1.914, 5.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.941 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.006 ms/op
Iteration   1: 3.355 ±(99.9%) 0.006 ms/op
Iteration   2: 3.468 ±(99.9%) 0.005 ms/op
Iteration   3: 3.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.432 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (3.355, 3.432, 3.472), stdev = 0.067
  CI (99.9%): [2.215, 4.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.527 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.004 ms/op
Iteration   1: 3.581 ±(99.9%) 0.004 ms/op
Iteration   2: 3.597 ±(99.9%) 0.003 ms/op
Iteration   3: 3.523 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.567 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (3.523, 3.567, 3.597), stdev = 0.039
  CI (99.9%): [2.860, 4.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.237 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.665 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.007 ms/op
Iteration   1: 4.337 ±(99.9%) 0.007 ms/op
Iteration   2: 4.262 ±(99.9%) 0.011 ms/op
Iteration   3: 4.086 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.228 ±(99.9%) 2.350 ms/op [Average]
  (min, avg, max) = (4.086, 4.228, 4.337), stdev = 0.129
  CI (99.9%): [1.878, 6.578] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.270 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.012 ms/op
Iteration   1: 3.740 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   6.513 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  13.895 ms/op
                 createUser·p0.9999: 23.968 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.627 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.606 ms/op
                 createUser·p0.99:   7.288 ms/op
                 createUser·p0.999:  23.290 ms/op
                 createUser·p0.9999: 26.417 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 3.544 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  25.715 ms/op
                 createUser·p0.9999: 31.915 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264131
  mean =      3.635 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5448 
    [ 2.500,  5.000) = 244854 
    [ 5.000,  7.500) = 11497 
    [ 7.500, 10.000) = 1657 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     21.880 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     32.270 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.988 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.009 ms/op
Iteration   1: 3.558 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.827 ms/op
                 existUser·p0.999:  18.153 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.502 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  19.814 ms/op
                 existUser·p0.9999: 22.802 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.589 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  22.774 ms/op
                 existUser·p0.9999: 25.663 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 270283
  mean =      3.549 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5604 
    [ 2.500,  5.000) = 254693 
    [ 5.000,  7.500) = 7978 
    [ 7.500, 10.000) = 1275 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.813 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.016 ms/op
Iteration   1: 3.727 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   7.864 ms/op
                 getUser·p0.999:  12.993 ms/op
                 getUser·p0.9999: 24.007 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.570 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  24.084 ms/op
                 getUser·p0.9999: 27.463 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.540 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  22.350 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265878
  mean =      3.611 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4279 
    [ 2.500,  5.000) = 251134 
    [ 5.000,  7.500) = 6911 
    [ 7.500, 10.000) = 2835 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     17.568 ms/op
     p(99.9900) =     29.453 ms/op
     p(99.9990) =     30.344 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.596 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.597 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.014 ms/op
Iteration   1: 4.346 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  19.890 ms/op
                 listUser·p0.9999: 22.106 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 4.198 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  16.117 ms/op
                 listUser·p0.9999: 21.573 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   3: 4.238 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 18.463 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225479
  mean =      4.260 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 211876 
    [ 5.000,  7.500) = 9198 
    [ 7.500, 10.000) = 3220 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 347 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     17.187 ms/op
     p(99.9900) =     21.511 ms/op
     p(99.9990) =     22.470 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.964 ± 3.562  ops/ms
ClientPb.existUser                       thrpt       3   9.329 ± 1.127  ops/ms
ClientPb.getUser                         thrpt       3   8.798 ± 5.619  ops/ms
ClientPb.listUser                        thrpt       3   7.524 ± 3.159  ops/ms
ClientPb.createUser                       avgt       3   3.572 ± 1.658   ms/op
ClientPb.existUser                        avgt       3   3.432 ± 1.217   ms/op
ClientPb.getUser                          avgt       3   3.567 ± 0.707   ms/op
ClientPb.listUser                         avgt       3   4.228 ± 2.350   ms/op
ClientPb.createUser                     sample  264131   3.635 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.145           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.490           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.408           ms/op
ClientPb.existUser                      sample  270283   3.549 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.196           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.387           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.225           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.399           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.478           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.575           ms/op
ClientPb.getUser                        sample  265878   3.611 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.988           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.733           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.568           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.453           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  225479   4.260 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.520           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.259           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.187           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.511           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
