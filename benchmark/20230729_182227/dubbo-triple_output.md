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
# Warmup Iteration   1: 1.574 ops/ms
# Warmup Iteration   2: 4.423 ops/ms
# Warmup Iteration   3: 7.521 ops/ms
Iteration   1: 7.520 ops/ms
Iteration   2: 8.352 ops/ms
Iteration   3: 8.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.035 ±(99.9%) 8.198 ops/ms [Average]
  (min, avg, max) = (7.520, 8.035, 8.352), stdev = 0.449
  CI (99.9%): [≈ 0, 16.232] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.280 ops/ms
# Warmup Iteration   2: 7.719 ops/ms
# Warmup Iteration   3: 8.130 ops/ms
Iteration   1: 8.605 ops/ms
Iteration   2: 8.629 ops/ms
Iteration   3: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.625 ±(99.9%) 0.337 ops/ms [Average]
  (min, avg, max) = (8.605, 8.625, 8.641), stdev = 0.018
  CI (99.9%): [8.288, 8.962] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.265 ops/ms
# Warmup Iteration   2: 6.339 ops/ms
# Warmup Iteration   3: 8.033 ops/ms
Iteration   1: 7.901 ops/ms
Iteration   2: 8.558 ops/ms
Iteration   3: 8.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.190 ±(99.9%) 6.120 ops/ms [Average]
  (min, avg, max) = (7.901, 8.190, 8.558), stdev = 0.335
  CI (99.9%): [2.070, 14.309] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.115 ops/ms
# Warmup Iteration   2: 6.183 ops/ms
# Warmup Iteration   3: 6.477 ops/ms
Iteration   1: 6.730 ops/ms
Iteration   2: 7.014 ops/ms
Iteration   3: 6.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.866 ±(99.9%) 2.592 ops/ms [Average]
  (min, avg, max) = (6.730, 6.866, 7.014), stdev = 0.142
  CI (99.9%): [4.274, 9.459] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.055 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.006 ms/op
Iteration   1: 3.841 ±(99.9%) 0.009 ms/op
Iteration   2: 3.918 ±(99.9%) 0.007 ms/op
Iteration   3: 3.830 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.863 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.830, 3.863, 3.918), stdev = 0.048
  CI (99.9%): [2.988, 4.738] (assumes normal distribution)


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
# Warmup Iteration   1: 11.047 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.008 ms/op
Iteration   1: 3.824 ±(99.9%) 0.011 ms/op
Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
Iteration   3: 3.606 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.682 ±(99.9%) 2.245 ms/op [Average]
  (min, avg, max) = (3.606, 3.682, 3.824), stdev = 0.123
  CI (99.9%): [1.437, 5.927] (assumes normal distribution)


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
# Warmup Iteration   1: 11.506 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.006 ms/op
Iteration   1: 3.950 ±(99.9%) 0.008 ms/op
Iteration   2: 3.738 ±(99.9%) 0.007 ms/op
Iteration   3: 3.666 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.785 ±(99.9%) 2.689 ms/op [Average]
  (min, avg, max) = (3.666, 3.785, 3.950), stdev = 0.147
  CI (99.9%): [1.096, 6.474] (assumes normal distribution)


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
# Warmup Iteration   1: 12.491 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.029 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.444 ±(99.9%) 0.014 ms/op
Iteration   1: 4.431 ±(99.9%) 0.011 ms/op
Iteration   2: 4.556 ±(99.9%) 0.012 ms/op
Iteration   3: 4.447 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.478 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (4.431, 4.478, 4.556), stdev = 0.068
  CI (99.9%): [3.240, 5.717] (assumes normal distribution)


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
# Warmup Iteration   1: 11.890 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.016 ms/op
Iteration   1: 3.707 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 24.883 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 3.714 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  24.289 ms/op
                 createUser·p0.9999: 26.615 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.861 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  14.601 ms/op
                 createUser·p0.9999: 32.342 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 255182
  mean =      3.759 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2636 
    [ 2.500,  5.000) = 240615 
    [ 5.000,  7.500) = 10196 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     21.230 ms/op
     p(99.9900) =     31.031 ms/op
     p(99.9990) =     32.958 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 11.366 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.012 ms/op
Iteration   1: 3.764 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 27.019 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   2: 3.624 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  10.299 ms/op
                 existUser·p0.9999: 25.804 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.686 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.045 ms/op
                 existUser·p0.999:  24.750 ms/op
                 existUser·p0.9999: 32.014 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 260040
  mean =      3.690 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2427 
    [ 2.500,  5.000) = 249321 
    [ 5.000,  7.500) = 6798 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     14.106 ms/op
     p(99.9900) =     30.408 ms/op
     p(99.9990) =     33.332 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 10.748 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.014 ms/op
Iteration   1: 3.690 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.553 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 23.866 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.814 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   7.963 ms/op
                 getUser·p0.999:  24.156 ms/op
                 getUser·p0.9999: 31.420 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   3: 3.726 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.329 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  24.963 ms/op
                 getUser·p0.9999: 28.263 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 256323
  mean =      3.743 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1152 
    [ 2.500,  5.000) = 245082 
    [ 5.000,  7.500) = 7469 
    [ 7.500, 10.000) = 1895 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     20.063 ms/op
     p(99.9900) =     30.400 ms/op
     p(99.9990) =     31.898 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 12.983 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.805 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.643 ±(99.9%) 0.016 ms/op
Iteration   1: 4.511 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  22.348 ms/op
                 listUser·p0.9999: 26.408 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 4.576 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.577 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.695 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  16.597 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 210727
  mean =      4.554 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 190506 
    [ 5.000,  7.500) = 16584 
    [ 7.500, 10.000) = 2503 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     19.473 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     26.659 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.035 ± 8.198  ops/ms
ClientPb.existUser                       thrpt       3   8.625 ± 0.337  ops/ms
ClientPb.getUser                         thrpt       3   8.190 ± 6.120  ops/ms
ClientPb.listUser                        thrpt       3   6.866 ± 2.592  ops/ms
ClientPb.createUser                       avgt       3   3.863 ± 0.875   ms/op
ClientPb.existUser                        avgt       3   3.682 ± 2.245   ms/op
ClientPb.getUser                          avgt       3   3.785 ± 2.689   ms/op
ClientPb.listUser                         avgt       3   4.478 ± 1.239   ms/op
ClientPb.createUser                     sample  255182   3.759 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.987           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.907           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.230           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.031           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.489           ms/op
ClientPb.existUser                      sample  260040   3.690 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.208           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.106           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.408           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  256323   3.743 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.063           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.400           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949           ms/op
ClientPb.listUser                       sample  210727   4.554 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.544           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.473           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.904           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
