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
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 4.070 ops/ms
# Warmup Iteration   3: 7.319 ops/ms
Iteration   1: 7.497 ops/ms
Iteration   2: 8.166 ops/ms
Iteration   3: 8.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.920 ±(99.9%) 6.711 ops/ms [Average]
  (min, avg, max) = (7.497, 7.920, 8.166), stdev = 0.368
  CI (99.9%): [1.209, 14.631] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.408 ops/ms
# Warmup Iteration   2: 6.827 ops/ms
# Warmup Iteration   3: 7.997 ops/ms
Iteration   1: 8.569 ops/ms
Iteration   2: 8.439 ops/ms
Iteration   3: 8.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.476 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (8.418, 8.476, 8.569), stdev = 0.082
  CI (99.9%): [6.981, 9.971] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.078 ops/ms
# Warmup Iteration   2: 6.497 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 8.104 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.002 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (7.901, 8.002, 8.104), stdev = 0.102
  CI (99.9%): [6.146, 9.857] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.116 ops/ms
# Warmup Iteration   2: 5.769 ops/ms
# Warmup Iteration   3: 6.594 ops/ms
Iteration   1: 7.026 ops/ms
Iteration   2: 6.586 ops/ms
Iteration   3: 7.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.919 ±(99.9%) 5.369 ops/ms [Average]
  (min, avg, max) = (6.586, 6.919, 7.144), stdev = 0.294
  CI (99.9%): [1.550, 12.288] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.099 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.005 ms/op
Iteration   1: 3.878 ±(99.9%) 0.014 ms/op
Iteration   2: 4.042 ±(99.9%) 0.008 ms/op
Iteration   3: 3.933 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.951 ±(99.9%) 1.527 ms/op [Average]
  (min, avg, max) = (3.878, 3.951, 4.042), stdev = 0.084
  CI (99.9%): [2.424, 5.477] (assumes normal distribution)


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
# Warmup Iteration   1: 12.424 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.008 ms/op
Iteration   1: 3.890 ±(99.9%) 0.007 ms/op
Iteration   2: 3.689 ±(99.9%) 0.010 ms/op
Iteration   3: 3.773 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.784 ±(99.9%) 1.842 ms/op [Average]
  (min, avg, max) = (3.689, 3.784, 3.890), stdev = 0.101
  CI (99.9%): [1.942, 5.626] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.481 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.932 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.009 ms/op
Iteration   1: 4.180 ±(99.9%) 0.008 ms/op
Iteration   2: 3.836 ±(99.9%) 0.012 ms/op
Iteration   3: 3.904 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.973 ±(99.9%) 3.326 ms/op [Average]
  (min, avg, max) = (3.836, 3.973, 4.180), stdev = 0.182
  CI (99.9%): [0.648, 7.299] (assumes normal distribution)


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
# Warmup Iteration   1: 12.785 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.408 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.017 ms/op
Iteration   1: 4.601 ±(99.9%) 0.012 ms/op
Iteration   2: 4.582 ±(99.9%) 0.021 ms/op
Iteration   3: 4.471 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.551 ±(99.9%) 1.276 ms/op [Average]
  (min, avg, max) = (4.471, 4.551, 4.601), stdev = 0.070
  CI (99.9%): [3.275, 5.827] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.039 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.076 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.418 ±(99.9%) 0.017 ms/op
Iteration   1: 3.949 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.089 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  24.214 ms/op
                 createUser·p0.9999: 32.863 ms/op
                 createUser·p1.00:   33.161 ms/op

Iteration   2: 3.966 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  24.909 ms/op
                 createUser·p0.9999: 27.327 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 3.952 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  16.714 ms/op
                 createUser·p0.9999: 36.891 ms/op
                 createUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242585
  mean =      3.955 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 411 
    [ 2.500,  5.000) = 231880 
    [ 5.000,  7.500) = 8758 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     23.896 ms/op
     p(99.9900) =     35.045 ms/op
     p(99.9990) =     37.356 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.487 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
Iteration   1: 3.884 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  11.611 ms/op
                 existUser·p0.9999: 24.193 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.742 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.828 ms/op
                 existUser·p0.999:  24.496 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   3: 3.966 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  10.338 ms/op
                 existUser·p0.9999: 31.258 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248440
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 254 
    [ 2.500,  5.000) = 238900 
    [ 5.000,  7.500) = 7855 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     29.396 ms/op
     p(99.9990) =     31.589 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 12.641 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.013 ms/op
Iteration   1: 3.999 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  23.331 ms/op
                 getUser·p0.9999: 26.313 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   2: 3.940 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  11.323 ms/op
                 getUser·p0.9999: 28.013 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   6.653 ms/op
                 getUser·p0.999:  26.883 ms/op
                 getUser·p0.9999: 30.184 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239792
  mean =      4.005 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 228242 
    [ 5.000,  7.500) = 9318 
    [ 7.500, 10.000) = 1578 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     23.331 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 12.061 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 5.796 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.797 ±(99.9%) 0.017 ms/op
Iteration   1: 4.795 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  23.207 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   2: 4.607 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 4.695 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  17.271 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204021
  mean =      4.698 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 170233 
    [ 5.000,  7.500) = 29732 
    [ 7.500, 10.000) = 3085 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      8.631 ms/op
     p(99.9000) =     19.495 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     25.292 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.920 ± 6.711  ops/ms
ClientPb.existUser                       thrpt       3   8.476 ± 1.495  ops/ms
ClientPb.getUser                         thrpt       3   8.002 ± 1.855  ops/ms
ClientPb.listUser                        thrpt       3   6.919 ± 5.369  ops/ms
ClientPb.createUser                       avgt       3   3.951 ± 1.527   ms/op
ClientPb.existUser                        avgt       3   3.784 ± 1.842   ms/op
ClientPb.getUser                          avgt       3   3.973 ± 3.326   ms/op
ClientPb.listUser                         avgt       3   4.551 ± 1.276   ms/op
ClientPb.createUser                     sample  242585   3.955 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.829           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.896           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.045           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.421           ms/op
ClientPb.existUser                      sample  248440   3.862 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.221           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.600           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.396           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.719           ms/op
ClientPb.getUser                        sample  239792   4.005 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.405           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.331           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.000           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  204021   4.698 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.419           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.631           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.495           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.347           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.179           ms/op
