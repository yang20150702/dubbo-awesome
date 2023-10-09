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
# Warmup Iteration   1: 2.021 ops/ms
# Warmup Iteration   2: 5.401 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.727 ops/ms
Iteration   2: 8.925 ops/ms
Iteration   3: 8.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.883 ±(99.9%) 2.561 ops/ms [Average]
  (min, avg, max) = (8.727, 8.883, 8.998), stdev = 0.140
  CI (99.9%): [6.322, 11.444] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.244 ops/ms
# Warmup Iteration   2: 8.602 ops/ms
# Warmup Iteration   3: 9.099 ops/ms
Iteration   1: 9.562 ops/ms
Iteration   2: 9.442 ops/ms
Iteration   3: 9.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.521 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (9.442, 9.521, 9.562), stdev = 0.068
  CI (99.9%): [8.280, 10.762] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.932 ops/ms
# Warmup Iteration   2: 8.524 ops/ms
# Warmup Iteration   3: 8.620 ops/ms
Iteration   1: 9.057 ops/ms
Iteration   2: 8.781 ops/ms
Iteration   3: 8.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.926 ±(99.9%) 2.521 ops/ms [Average]
  (min, avg, max) = (8.781, 8.926, 9.057), stdev = 0.138
  CI (99.9%): [6.405, 11.448] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.401 ops/ms
# Warmup Iteration   2: 7.013 ops/ms
# Warmup Iteration   3: 7.388 ops/ms
Iteration   1: 7.530 ops/ms
Iteration   2: 7.546 ops/ms
Iteration   3: 7.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.537 ±(99.9%) 0.153 ops/ms [Average]
  (min, avg, max) = (7.530, 7.537, 7.546), stdev = 0.008
  CI (99.9%): [7.384, 7.691] (assumes normal distribution)


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
# Warmup Iteration   1: 12.225 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.004 ms/op
Iteration   1: 3.652 ±(99.9%) 0.009 ms/op
Iteration   2: 3.550 ±(99.9%) 0.005 ms/op
Iteration   3: 3.581 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.594 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (3.550, 3.594, 3.652), stdev = 0.052
  CI (99.9%): [2.640, 4.549] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.032 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.003 ms/op
Iteration   1: 3.441 ±(99.9%) 0.005 ms/op
Iteration   2: 3.485 ±(99.9%) 0.005 ms/op
Iteration   3: 3.371 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.432 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (3.371, 3.432, 3.485), stdev = 0.057
  CI (99.9%): [2.383, 4.481] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.952 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.004 ms/op
Iteration   1: 3.603 ±(99.9%) 0.005 ms/op
Iteration   2: 3.564 ±(99.9%) 0.006 ms/op
Iteration   3: 3.598 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.588 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.564, 3.588, 3.603), stdev = 0.021
  CI (99.9%): [3.202, 3.975] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.919 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.008 ms/op
Iteration   1: 4.223 ±(99.9%) 0.010 ms/op
Iteration   2: 4.242 ±(99.9%) 0.015 ms/op
Iteration   3: 4.187 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.217 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (4.187, 4.217, 4.242), stdev = 0.028
  CI (99.9%): [3.711, 4.723] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.527 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.015 ms/op
Iteration   1: 3.504 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  21.420 ms/op
                 createUser·p0.9999: 23.322 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 3.595 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  21.822 ms/op
                 createUser·p0.9999: 25.333 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 3.541 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  21.850 ms/op
                 createUser·p0.9999: 26.406 ms/op
                 createUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270749
  mean =      3.546 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5019 
    [ 2.500,  5.000) = 256057 
    [ 5.000,  7.500) = 7554 
    [ 7.500, 10.000) = 1398 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     25.393 ms/op
     p(99.9990) =     26.862 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.093 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.009 ms/op
Iteration   1: 3.429 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  18.800 ms/op
                 existUser·p0.9999: 20.731 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.372 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  18.931 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 3.407 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  14.565 ms/op
                 existUser·p0.9999: 26.005 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281932
  mean =      3.403 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7356 
    [ 2.500,  5.000) = 265674 
    [ 5.000,  7.500) = 7380 
    [ 7.500, 10.000) = 965 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.238 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     16.198 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     26.456 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 9.082 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.013 ms/op
Iteration   1: 3.542 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   8.135 ms/op
                 getUser·p0.999:  12.822 ms/op
                 getUser·p0.9999: 23.622 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.507 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.416 ms/op
                 getUser·p0.999:  23.390 ms/op
                 getUser·p0.9999: 26.964 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.617 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  18.121 ms/op
                 getUser·p0.9999: 26.815 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269931
  mean =      3.555 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4115 
    [ 2.500,  5.000) = 255720 
    [ 5.000,  7.500) = 7796 
    [ 7.500, 10.000) = 1460 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     27.965 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 10.753 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.014 ms/op
Iteration   1: 4.377 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   8.627 ms/op
                 listUser·p0.999:  20.347 ms/op
                 listUser·p0.9999: 49.223 ms/op
                 listUser·p1.00:   61.080 ms/op

Iteration   2: 4.282 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.328 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  16.196 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.306 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   4.174 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.791 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222024
  mean =      4.321 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 205870 
    [ 5.000, 10.000) = 15049 
    [10.000, 15.000) = 631 
    [15.000, 20.000) = 387 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 24 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     16.449 ms/op
     p(99.9900) =     45.403 ms/op
     p(99.9990) =     58.904 ms/op
     p(99.9999) =     61.080 ms/op
    p(100.0000) =     61.080 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.883 ± 2.561  ops/ms
ClientPb.existUser                       thrpt       3   9.521 ± 1.241  ops/ms
ClientPb.getUser                         thrpt       3   8.926 ± 2.521  ops/ms
ClientPb.listUser                        thrpt       3   7.537 ± 0.153  ops/ms
ClientPb.createUser                       avgt       3   3.594 ± 0.955   ms/op
ClientPb.existUser                        avgt       3   3.432 ± 1.049   ms/op
ClientPb.getUser                          avgt       3   3.588 ± 0.386   ms/op
ClientPb.listUser                         avgt       3   4.217 ± 0.506   ms/op
ClientPb.createUser                     sample  270749   3.546 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.116           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.627           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.393           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.460           ms/op
ClientPb.existUser                      sample  281932   3.403 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.370           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.238           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.198           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.297           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.673           ms/op
ClientPb.getUser                        sample  269931   3.555 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.153           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.739           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  222024   4.321 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.399           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.667           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.449           ms/op
ClientPb.listUser:listUser·p0.9999      sample          45.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          61.080           ms/op
