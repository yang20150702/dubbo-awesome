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
# Warmup Iteration   1: 1.506 ops/ms
# Warmup Iteration   2: 3.508 ops/ms
# Warmup Iteration   3: 7.154 ops/ms
Iteration   1: 7.500 ops/ms
Iteration   2: 7.763 ops/ms
Iteration   3: 7.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.670 ±(99.9%) 2.686 ops/ms [Average]
  (min, avg, max) = (7.500, 7.670, 7.763), stdev = 0.147
  CI (99.9%): [4.984, 10.356] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.145 ops/ms
# Warmup Iteration   2: 6.806 ops/ms
# Warmup Iteration   3: 7.996 ops/ms
Iteration   1: 8.297 ops/ms
Iteration   2: 8.203 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.247 ±(99.9%) 0.858 ops/ms [Average]
  (min, avg, max) = (8.203, 8.247, 8.297), stdev = 0.047
  CI (99.9%): [7.389, 9.106] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.048 ops/ms
# Warmup Iteration   2: 6.177 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 7.884 ops/ms
Iteration   2: 7.930 ops/ms
Iteration   3: 7.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.906 ±(99.9%) 0.428 ops/ms [Average]
  (min, avg, max) = (7.884, 7.906, 7.930), stdev = 0.023
  CI (99.9%): [7.479, 8.334] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.134 ops/ms
# Warmup Iteration   2: 5.478 ops/ms
# Warmup Iteration   3: 6.612 ops/ms
Iteration   1: 6.573 ops/ms
Iteration   2: 6.540 ops/ms
Iteration   3: 6.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.617 ±(99.9%) 1.946 ops/ms [Average]
  (min, avg, max) = (6.540, 6.617, 6.739), stdev = 0.107
  CI (99.9%): [4.672, 8.563] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.530 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.004 ms/op
Iteration   1: 4.106 ±(99.9%) 0.005 ms/op
Iteration   2: 3.980 ±(99.9%) 0.004 ms/op
Iteration   3: 3.901 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.995 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (3.901, 3.995, 4.106), stdev = 0.103
  CI (99.9%): [2.110, 5.881] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.171 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.004 ms/op
Iteration   1: 3.793 ±(99.9%) 0.006 ms/op
Iteration   2: 3.815 ±(99.9%) 0.004 ms/op
Iteration   3: 3.823 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.810 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (3.793, 3.810, 3.823), stdev = 0.015
  CI (99.9%): [3.532, 4.088] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.426 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.004 ms/op
Iteration   1: 4.108 ±(99.9%) 0.003 ms/op
Iteration   2: 4.001 ±(99.9%) 0.003 ms/op
Iteration   3: 3.961 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.023 ±(99.9%) 1.392 ms/op [Average]
  (min, avg, max) = (3.961, 4.023, 4.108), stdev = 0.076
  CI (99.9%): [2.631, 5.415] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.351 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.812 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.864 ±(99.9%) 0.008 ms/op
Iteration   1: 4.694 ±(99.9%) 0.009 ms/op
Iteration   2: 4.690 ±(99.9%) 0.011 ms/op
Iteration   3: 4.771 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.718 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (4.690, 4.718, 4.771), stdev = 0.046
  CI (99.9%): [3.885, 5.552] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.071 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 4.905 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.393 ±(99.9%) 0.018 ms/op
Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  22.053 ms/op
                 createUser·p0.9999: 26.083 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 3.979 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  25.772 ms/op
                 createUser·p0.9999: 28.965 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   3: 3.996 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.034 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.689 ms/op
                 createUser·p0.999:  16.939 ms/op
                 createUser·p0.9999: 30.441 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240764
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 468 
    [ 2.500,  5.000) = 228669 
    [ 5.000,  7.500) = 9747 
    [ 7.500, 10.000) = 1097 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     21.708 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     30.781 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 9.776 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.010 ms/op
Iteration   1: 3.849 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  10.069 ms/op
                 existUser·p0.9999: 22.855 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 3.865 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  13.009 ms/op
                 existUser·p0.9999: 24.951 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   3: 3.861 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.845 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   7.987 ms/op
                 existUser·p0.999:  24.838 ms/op
                 existUser·p0.9999: 27.188 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248677
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 499 
    [ 2.500,  5.000) = 238618 
    [ 5.000,  7.500) = 7430 
    [ 7.500, 10.000) = 1368 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.309 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     26.448 ms/op
     p(99.9990) =     27.807 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.913 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.013 ms/op
Iteration   1: 4.007 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   8.241 ms/op
                 getUser·p0.999:  23.206 ms/op
                 getUser·p0.9999: 27.724 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   2: 3.861 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  16.273 ms/op
                 getUser·p0.9999: 28.869 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   3: 3.893 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  26.804 ms/op
                 getUser·p0.9999: 30.347 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244803
  mean =      3.919 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 221 
    [ 2.500,  5.000) = 234876 
    [ 5.000,  7.500) = 7457 
    [ 7.500, 10.000) = 1386 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     22.950 ms/op
     p(99.9900) =     29.067 ms/op
     p(99.9990) =     30.940 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.526 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.688 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.831 ±(99.9%) 0.015 ms/op
Iteration   1: 4.914 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   10.279 ms/op
                 listUser·p0.999:  26.018 ms/op
                 listUser·p0.9999: 28.130 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   2: 4.817 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  17.649 ms/op
                 listUser·p0.9999: 20.941 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   3: 4.786 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 18.721 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198525
  mean =      4.839 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 148409 
    [ 5.000,  7.500) = 45920 
    [ 7.500, 10.000) = 3031 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     20.478 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     28.771 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.670 ± 2.686  ops/ms
ClientPb.existUser                       thrpt       3   8.247 ± 0.858  ops/ms
ClientPb.getUser                         thrpt       3   7.906 ± 0.428  ops/ms
ClientPb.listUser                        thrpt       3   6.617 ± 1.946  ops/ms
ClientPb.createUser                       avgt       3   3.995 ± 1.886   ms/op
ClientPb.existUser                        avgt       3   3.810 ± 0.278   ms/op
ClientPb.getUser                          avgt       3   4.023 ± 1.392   ms/op
ClientPb.listUser                         avgt       3   4.718 ± 0.833   ms/op
ClientPb.createUser                     sample  240764   3.987 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.135           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.708           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.835           ms/op
ClientPb.existUser                      sample  248677   3.858 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.368           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.309           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.448           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.312           ms/op
ClientPb.getUser                        sample  244803   3.919 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.950           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.067           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.031           ms/op
ClientPb.listUser                       sample  198525   4.839 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.331           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.478           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.460           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.836           ms/op
