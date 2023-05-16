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
# Warmup Iteration   1: 1.494 ops/ms
# Warmup Iteration   2: 3.949 ops/ms
# Warmup Iteration   3: 7.257 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 8.510 ops/ms
Iteration   3: 8.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.270 ±(99.9%) 6.077 ops/ms [Average]
  (min, avg, max) = (7.889, 8.270, 8.510), stdev = 0.333
  CI (99.9%): [2.193, 14.346] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.294 ops/ms
# Warmup Iteration   2: 7.091 ops/ms
# Warmup Iteration   3: 8.533 ops/ms
Iteration   1: 8.267 ops/ms
Iteration   2: 8.409 ops/ms
Iteration   3: 8.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.434 ±(99.9%) 3.293 ops/ms [Average]
  (min, avg, max) = (8.267, 8.434, 8.626), stdev = 0.181
  CI (99.9%): [5.140, 11.727] (assumes normal distribution)


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
# Warmup Iteration   1: 2.464 ops/ms
# Warmup Iteration   2: 6.893 ops/ms
# Warmup Iteration   3: 8.396 ops/ms
Iteration   1: 8.298 ops/ms
Iteration   2: 8.007 ops/ms
Iteration   3: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.272 ±(99.9%) 4.617 ops/ms [Average]
  (min, avg, max) = (8.007, 8.272, 8.512), stdev = 0.253
  CI (99.9%): [3.655, 12.890] (assumes normal distribution)


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
# Warmup Iteration   1: 2.212 ops/ms
# Warmup Iteration   2: 5.788 ops/ms
# Warmup Iteration   3: 6.758 ops/ms
Iteration   1: 6.990 ops/ms
Iteration   2: 7.109 ops/ms
Iteration   3: 7.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.086 ±(99.9%) 1.579 ops/ms [Average]
  (min, avg, max) = (6.990, 7.086, 7.158), stdev = 0.087
  CI (99.9%): [5.507, 8.665] (assumes normal distribution)


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
# Warmup Iteration   1: 13.400 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.875 ±(99.9%) 0.005 ms/op
Iteration   2: 3.950 ±(99.9%) 0.006 ms/op
Iteration   3: 3.874 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.899 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.874, 3.899, 3.950), stdev = 0.044
  CI (99.9%): [3.103, 4.696] (assumes normal distribution)


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
# Warmup Iteration   1: 10.316 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.008 ms/op
Iteration   1: 3.664 ±(99.9%) 0.009 ms/op
Iteration   2: 3.747 ±(99.9%) 0.010 ms/op
Iteration   3: 3.698 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.703 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.664, 3.703, 3.747), stdev = 0.041
  CI (99.9%): [2.947, 4.459] (assumes normal distribution)


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
# Warmup Iteration   1: 11.885 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.003 ms/op
Iteration   1: 3.885 ±(99.9%) 0.007 ms/op
Iteration   2: 3.753 ±(99.9%) 0.010 ms/op
Iteration   3: 3.819 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.819 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.753, 3.819, 3.885), stdev = 0.066
  CI (99.9%): [2.619, 5.019] (assumes normal distribution)


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
# Warmup Iteration   1: 12.556 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.428 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.647 ±(99.9%) 0.013 ms/op
Iteration   1: 4.522 ±(99.9%) 0.009 ms/op
Iteration   2: 4.447 ±(99.9%) 0.014 ms/op
Iteration   3: 4.521 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.497 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (4.447, 4.497, 4.522), stdev = 0.043
  CI (99.9%): [3.710, 5.283] (assumes normal distribution)


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
# Warmup Iteration   1: 11.034 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 5.785 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.018 ms/op
Iteration   1: 3.938 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  23.900 ms/op
                 createUser·p0.9999: 27.193 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   2: 3.919 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  22.526 ms/op
                 createUser·p0.9999: 28.593 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 3.820 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.911 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  27.004 ms/op
                 createUser·p0.9999: 33.378 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246791
  mean =      3.892 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 767 
    [ 2.500,  5.000) = 236840 
    [ 5.000,  7.500) = 7560 
    [ 7.500, 10.000) = 917 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     23.770 ms/op
     p(99.9900) =     32.210 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 11.568 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.012 ms/op
Iteration   1: 3.721 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.731 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  12.076 ms/op
                 existUser·p0.9999: 28.098 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   2: 3.727 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.909 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  25.216 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  11.113 ms/op
                 existUser·p0.9999: 31.392 ms/op
                 existUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253111
  mean =      3.790 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 951 
    [ 2.500,  5.000) = 243043 
    [ 5.000,  7.500) = 7929 
    [ 7.500, 10.000) = 833 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 128 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     12.090 ms/op
     p(99.9900) =     29.612 ms/op
     p(99.9990) =     33.037 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 13.075 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.579 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.015 ms/op
Iteration   1: 3.877 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.028 ms/op
                 getUser·p0.999:  23.003 ms/op
                 getUser·p0.9999: 58.720 ms/op
                 getUser·p1.00:   59.376 ms/op

Iteration   2: 3.789 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.386 ms/op
                 getUser·p0.999:  24.707 ms/op
                 getUser·p0.9999: 28.923 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   3: 3.793 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.847 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  12.350 ms/op
                 getUser·p0.9999: 27.886 ms/op
                 getUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 251215
  mean =      3.819 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 242893 
    [ 5.000, 10.000) = 7937 
    [10.000, 15.000) = 128 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 57 
    [25.000, 30.000) = 165 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     22.097 ms/op
     p(99.9900) =     57.008 ms/op
     p(99.9990) =     59.145 ms/op
     p(99.9999) =     59.376 ms/op
    p(100.0000) =     59.376 ms/op


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
# Warmup Iteration   1: 12.092 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.085 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.724 ±(99.9%) 0.018 ms/op
Iteration   1: 4.530 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  26.752 ms/op
                 listUser·p0.9999: 31.717 ms/op
                 listUser·p1.00:   32.211 ms/op

Iteration   2: 4.380 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 22.800 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 4.600 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  19.577 ms/op
                 listUser·p0.9999: 22.982 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 213163
  mean =      4.501 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 193325 
    [ 5.000,  7.500) = 15740 
    [ 7.500, 10.000) = 3292 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     21.032 ms/op
     p(99.9900) =     30.540 ms/op
     p(99.9990) =     32.211 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.270 ± 6.077  ops/ms
ClientPb.existUser                       thrpt       3   8.434 ± 3.293  ops/ms
ClientPb.getUser                         thrpt       3   8.272 ± 4.617  ops/ms
ClientPb.listUser                        thrpt       3   7.086 ± 1.579  ops/ms
ClientPb.createUser                       avgt       3   3.899 ± 0.796   ms/op
ClientPb.existUser                        avgt       3   3.703 ± 0.756   ms/op
ClientPb.getUser                          avgt       3   3.819 ± 1.200   ms/op
ClientPb.listUser                         avgt       3   4.497 ± 0.787   ms/op
ClientPb.createUser                     sample  246791   3.892 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.477           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.770           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.210           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  253111   3.790 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.731           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.090           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.612           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.260           ms/op
ClientPb.getUser                        sample  251215   3.819 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.097           ms/op
ClientPb.getUser:getUser·p0.9999        sample          57.008           ms/op
ClientPb.getUser:getUser·p1.00          sample          59.376           ms/op
ClientPb.listUser                       sample  213163   4.501 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.329           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.964           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.032           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.540           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.211           ms/op
