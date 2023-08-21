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
# Warmup Iteration   1: 1.850 ops/ms
# Warmup Iteration   2: 3.902 ops/ms
# Warmup Iteration   3: 7.392 ops/ms
Iteration   1: 7.509 ops/ms
Iteration   2: 8.442 ops/ms
Iteration   3: 8.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.131 ±(99.9%) 9.837 ops/ms [Average]
  (min, avg, max) = (7.509, 8.131, 8.443), stdev = 0.539
  CI (99.9%): [≈ 0, 17.968] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.433 ops/ms
# Warmup Iteration   2: 7.972 ops/ms
# Warmup Iteration   3: 9.075 ops/ms
Iteration   1: 9.603 ops/ms
Iteration   2: 8.899 ops/ms
Iteration   3: 8.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.158 ±(99.9%) 7.063 ops/ms [Average]
  (min, avg, max) = (8.899, 9.158, 9.603), stdev = 0.387
  CI (99.9%): [2.095, 16.221] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.860 ops/ms
# Warmup Iteration   2: 7.744 ops/ms
# Warmup Iteration   3: 8.423 ops/ms
Iteration   1: 8.232 ops/ms
Iteration   2: 8.808 ops/ms
Iteration   3: 8.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.586 ±(99.9%) 5.662 ops/ms [Average]
  (min, avg, max) = (8.232, 8.586, 8.808), stdev = 0.310
  CI (99.9%): [2.925, 14.248] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.119 ops/ms
# Warmup Iteration   2: 5.827 ops/ms
# Warmup Iteration   3: 7.140 ops/ms
Iteration   1: 7.344 ops/ms
Iteration   2: 7.382 ops/ms
Iteration   3: 7.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.409 ±(99.9%) 1.494 ops/ms [Average]
  (min, avg, max) = (7.344, 7.409, 7.501), stdev = 0.082
  CI (99.9%): [5.915, 8.903] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.815 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.005 ms/op
Iteration   1: 3.817 ±(99.9%) 0.007 ms/op
Iteration   2: 3.913 ±(99.9%) 0.005 ms/op
Iteration   3: 3.592 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.774 ±(99.9%) 3.011 ms/op [Average]
  (min, avg, max) = (3.592, 3.774, 3.913), stdev = 0.165
  CI (99.9%): [0.763, 6.784] (assumes normal distribution)


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
# Warmup Iteration   1: 10.571 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.006 ms/op
Iteration   1: 3.499 ±(99.9%) 0.010 ms/op
Iteration   2: 3.635 ±(99.9%) 0.005 ms/op
Iteration   3: 3.693 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.609 ±(99.9%) 1.816 ms/op [Average]
  (min, avg, max) = (3.499, 3.609, 3.693), stdev = 0.100
  CI (99.9%): [1.793, 5.425] (assumes normal distribution)


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
# Warmup Iteration   1: 10.794 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.003 ms/op
Iteration   1: 4.007 ±(99.9%) 0.005 ms/op
Iteration   2: 4.150 ±(99.9%) 0.006 ms/op
Iteration   3: 3.629 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.928 ±(99.9%) 4.911 ms/op [Average]
  (min, avg, max) = (3.629, 3.928, 4.150), stdev = 0.269
  CI (99.9%): [≈ 0, 8.840] (assumes normal distribution)


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
# Warmup Iteration   1: 11.247 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.650 ±(99.9%) 0.005 ms/op
Iteration   1: 4.267 ±(99.9%) 0.006 ms/op
Iteration   2: 4.374 ±(99.9%) 0.012 ms/op
Iteration   3: 4.644 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.428 ±(99.9%) 3.550 ms/op [Average]
  (min, avg, max) = (4.267, 4.428, 4.644), stdev = 0.195
  CI (99.9%): [0.878, 7.978] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.648 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.970 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.015 ms/op
Iteration   1: 3.798 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  22.137 ms/op
                 createUser·p0.9999: 25.906 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 4.080 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.325 ms/op
                 createUser·p0.99:   7.922 ms/op
                 createUser·p0.999:  25.902 ms/op
                 createUser·p0.9999: 30.218 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 3.916 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.456 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  19.015 ms/op
                 createUser·p0.9999: 33.156 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244161
  mean =      3.928 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 987 
    [ 2.500,  5.000) = 226303 
    [ 5.000,  7.500) = 14475 
    [ 7.500, 10.000) = 1598 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     22.153 ms/op
     p(99.9900) =     31.509 ms/op
     p(99.9990) =     33.788 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.796 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.013 ms/op
Iteration   1: 3.623 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.864 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  11.103 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 4.014 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.881 ms/op
                 existUser·p0.999:  25.156 ms/op
                 existUser·p0.9999: 27.559 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   3: 3.731 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   7.807 ms/op
                 existUser·p0.999:  13.358 ms/op
                 existUser·p0.9999: 33.325 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253747
  mean =      3.782 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 944 
    [ 2.500,  5.000) = 241655 
    [ 5.000,  7.500) = 8550 
    [ 7.500, 10.000) = 1878 
    [10.000, 12.500) = 455 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.541 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     31.728 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 10.903 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.333 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.016 ms/op
Iteration   1: 3.544 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.833 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  21.512 ms/op
                 getUser·p0.9999: 24.312 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.746 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  10.776 ms/op
                 getUser·p0.9999: 27.785 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.708 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  26.433 ms/op
                 getUser·p0.9999: 31.666 ms/op
                 getUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 261911
  mean =      3.664 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4689 
    [ 2.500,  5.000) = 245935 
    [ 5.000,  7.500) = 8943 
    [ 7.500, 10.000) = 1736 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     12.635 ms/op
     p(99.9900) =     30.483 ms/op
     p(99.9990) =     33.022 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 12.684 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 4.848 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.576 ±(99.9%) 0.018 ms/op
Iteration   1: 4.412 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  22.766 ms/op
                 listUser·p0.9999: 25.419 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 4.467 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 19.876 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 4.499 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  17.399 ms/op
                 listUser·p0.9999: 19.952 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 215281
  mean =      4.459 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 189871 
    [ 5.000,  7.500) = 20249 
    [ 7.500, 10.000) = 3504 
    [10.000, 12.500) = 873 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     18.275 ms/op
     p(99.9900) =     24.460 ms/op
     p(99.9990) =     25.834 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.131 ± 9.837  ops/ms
ClientPb.existUser                       thrpt       3   9.158 ± 7.063  ops/ms
ClientPb.getUser                         thrpt       3   8.586 ± 5.662  ops/ms
ClientPb.listUser                        thrpt       3   7.409 ± 1.494  ops/ms
ClientPb.createUser                       avgt       3   3.774 ± 3.011   ms/op
ClientPb.existUser                        avgt       3   3.609 ± 1.816   ms/op
ClientPb.getUser                          avgt       3   3.928 ± 4.911   ms/op
ClientPb.listUser                         avgt       3   4.428 ± 3.550   ms/op
ClientPb.createUser                     sample  244161   3.928 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.456           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.447           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.153           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.509           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  253747   3.782 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.008           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.874           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.541           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.728           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  261911   3.664 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.282           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.555           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.258           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.635           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.483           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.522           ms/op
ClientPb.listUser                       sample  215281   4.459 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.118           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.275           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.460           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.477           ms/op
