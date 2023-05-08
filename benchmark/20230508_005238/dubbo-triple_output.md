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
# Warmup Iteration   1: 1.654 ops/ms
# Warmup Iteration   2: 3.809 ops/ms
# Warmup Iteration   3: 7.403 ops/ms
Iteration   1: 7.560 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.938 ±(99.9%) 5.982 ops/ms [Average]
  (min, avg, max) = (7.560, 7.938, 8.154), stdev = 0.328
  CI (99.9%): [1.956, 13.919] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.304 ops/ms
# Warmup Iteration   2: 6.872 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 8.301 ops/ms
Iteration   2: 8.767 ops/ms
Iteration   3: 8.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.601 ±(99.9%) 4.747 ops/ms [Average]
  (min, avg, max) = (8.301, 8.601, 8.767), stdev = 0.260
  CI (99.9%): [3.855, 13.348] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 7.133 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.130 ops/ms
Iteration   2: 8.138 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.136 ±(99.9%) 0.084 ops/ms [Average]
  (min, avg, max) = (8.130, 8.136, 8.139), stdev = 0.005
  CI (99.9%): [8.052, 8.219] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 5.518 ops/ms
# Warmup Iteration   3: 6.790 ops/ms
Iteration   1: 6.814 ops/ms
Iteration   2: 6.856 ops/ms
Iteration   3: 6.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.848 ±(99.9%) 0.556 ops/ms [Average]
  (min, avg, max) = (6.814, 6.848, 6.873), stdev = 0.030
  CI (99.9%): [6.292, 7.403] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.975 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.568 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.008 ms/op
Iteration   1: 4.077 ±(99.9%) 0.006 ms/op
Iteration   2: 3.853 ±(99.9%) 0.009 ms/op
Iteration   3: 4.041 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.990 ±(99.9%) 2.202 ms/op [Average]
  (min, avg, max) = (3.853, 3.990, 4.077), stdev = 0.121
  CI (99.9%): [1.788, 6.193] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.636 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.003 ms/op
Iteration   1: 3.809 ±(99.9%) 0.004 ms/op
Iteration   2: 3.727 ±(99.9%) 0.005 ms/op
Iteration   3: 3.624 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.720 ±(99.9%) 1.697 ms/op [Average]
  (min, avg, max) = (3.624, 3.720, 3.809), stdev = 0.093
  CI (99.9%): [2.023, 5.417] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.344 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.005 ms/op
Iteration   1: 3.960 ±(99.9%) 0.005 ms/op
Iteration   2: 3.928 ±(99.9%) 0.008 ms/op
Iteration   3: 3.845 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.911 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (3.845, 3.911, 3.960), stdev = 0.060
  CI (99.9%): [2.824, 4.997] (assumes normal distribution)


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
# Warmup Iteration   1: 12.615 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.178 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.607 ±(99.9%) 0.013 ms/op
Iteration   1: 4.475 ±(99.9%) 0.015 ms/op
Iteration   2: 4.647 ±(99.9%) 0.007 ms/op
Iteration   3: 4.600 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.574 ±(99.9%) 1.614 ms/op [Average]
  (min, avg, max) = (4.475, 4.574, 4.647), stdev = 0.088
  CI (99.9%): [2.960, 6.188] (assumes normal distribution)


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
# Warmup Iteration   1: 12.965 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.015 ms/op
Iteration   1: 3.942 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.870 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  22.741 ms/op
                 createUser·p0.9999: 27.783 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 3.836 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  24.374 ms/op
                 createUser·p0.9999: 26.749 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   3: 3.912 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.976 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  18.219 ms/op
                 createUser·p0.9999: 30.633 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246177
  mean =      3.896 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 291 
    [ 2.500,  5.000) = 235759 
    [ 5.000,  7.500) = 8631 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     22.637 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     32.229 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 10.798 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.010 ms/op
Iteration   1: 3.772 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.729 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  12.040 ms/op
                 existUser·p0.9999: 22.450 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.881 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.390 ms/op
                 existUser·p0.999:  22.925 ms/op
                 existUser·p0.9999: 26.945 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.728 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  10.340 ms/op
                 existUser·p0.9999: 25.975 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252994
  mean =      3.793 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 571 
    [ 2.500,  5.000) = 243851 
    [ 5.000,  7.500) = 7140 
    [ 7.500, 10.000) = 863 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     25.844 ms/op
     p(99.9990) =     27.918 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.652 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.014 ms/op
Iteration   1: 4.062 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   6.570 ms/op
                 getUser·p0.99:   9.709 ms/op
                 getUser·p0.999:  19.907 ms/op
                 getUser·p0.9999: 25.268 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.974 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  25.526 ms/op
                 getUser·p0.9999: 28.535 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   3: 3.769 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.436 ms/op
                 getUser·p0.999:  12.814 ms/op
                 getUser·p0.9999: 45.516 ms/op
                 getUser·p1.00:   48.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244028
  mean =      3.931 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 232876 
    [ 5.000, 10.000) = 10214 
    [10.000, 15.000) = 676 
    [15.000, 20.000) = 25 
    [20.000, 25.000) = 76 
    [25.000, 30.000) = 126 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.846 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     42.794 ms/op
     p(99.9990) =     46.378 ms/op
     p(99.9999) =     48.497 ms/op
    p(100.0000) =     48.497 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.332 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.157 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.659 ±(99.9%) 0.014 ms/op
Iteration   1: 4.588 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  22.457 ms/op
                 listUser·p0.9999: 25.234 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 4.546 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   8.992 ms/op
                 listUser·p0.999:  18.855 ms/op
                 listUser·p0.9999: 22.238 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   3: 4.405 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  15.971 ms/op
                 listUser·p0.9999: 18.079 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212581
  mean =      4.511 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 192292 
    [ 5.000,  7.500) = 16668 
    [ 7.500, 10.000) = 2571 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     24.788 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.938 ± 5.982  ops/ms
ClientPb.existUser                       thrpt       3   8.601 ± 4.747  ops/ms
ClientPb.getUser                         thrpt       3   8.136 ± 0.084  ops/ms
ClientPb.listUser                        thrpt       3   6.848 ± 0.556  ops/ms
ClientPb.createUser                       avgt       3   3.990 ± 2.202   ms/op
ClientPb.existUser                        avgt       3   3.720 ± 1.697   ms/op
ClientPb.getUser                          avgt       3   3.911 ± 1.086   ms/op
ClientPb.listUser                         avgt       3   4.574 ± 1.614   ms/op
ClientPb.createUser                     sample  246177   3.896 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.769           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.840           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.637           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.426           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.276           ms/op
ClientPb.existUser                      sample  252994   3.793 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.710           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.653           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.844           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.115           ms/op
ClientPb.getUser                        sample  244028   3.931 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.846           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.028           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.383           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.794           ms/op
ClientPb.getUser:getUser·p1.00          sample          48.497           ms/op
ClientPb.listUser                       sample  212581   4.511 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.204           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.285           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.788           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.361           ms/op
