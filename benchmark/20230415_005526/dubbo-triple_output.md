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
# Warmup Iteration   1: 1.692 ops/ms
# Warmup Iteration   2: 4.104 ops/ms
# Warmup Iteration   3: 7.494 ops/ms
Iteration   1: 7.624 ops/ms
Iteration   2: 8.136 ops/ms
Iteration   3: 8.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.037 ±(99.9%) 6.814 ops/ms [Average]
  (min, avg, max) = (7.624, 8.037, 8.352), stdev = 0.373
  CI (99.9%): [1.224, 14.851] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.446 ops/ms
# Warmup Iteration   2: 6.814 ops/ms
# Warmup Iteration   3: 8.264 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 8.546 ops/ms
Iteration   3: 8.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.347 ±(99.9%) 3.719 ops/ms [Average]
  (min, avg, max) = (8.139, 8.347, 8.546), stdev = 0.204
  CI (99.9%): [4.628, 12.066] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.561 ops/ms
# Warmup Iteration   2: 6.560 ops/ms
# Warmup Iteration   3: 7.782 ops/ms
Iteration   1: 8.290 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 8.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.190 ±(99.9%) 1.572 ops/ms [Average]
  (min, avg, max) = (8.137, 8.190, 8.290), stdev = 0.086
  CI (99.9%): [6.619, 9.762] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.296 ops/ms
# Warmup Iteration   2: 5.977 ops/ms
# Warmup Iteration   3: 6.943 ops/ms
Iteration   1: 7.166 ops/ms
Iteration   2: 7.005 ops/ms
Iteration   3: 6.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.011 ±(99.9%) 2.770 ops/ms [Average]
  (min, avg, max) = (6.862, 7.011, 7.166), stdev = 0.152
  CI (99.9%): [4.241, 9.781] (assumes normal distribution)


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
# Warmup Iteration   1: 11.085 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.009 ms/op
Iteration   1: 3.940 ±(99.9%) 0.009 ms/op
Iteration   2: 3.900 ±(99.9%) 0.006 ms/op
Iteration   3: 3.871 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.904 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (3.871, 3.904, 3.940), stdev = 0.035
  CI (99.9%): [3.272, 4.535] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.120 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.005 ms/op
Iteration   1: 3.744 ±(99.9%) 0.006 ms/op
Iteration   2: 3.800 ±(99.9%) 0.004 ms/op
Iteration   3: 3.837 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.794 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.744, 3.794, 3.837), stdev = 0.047
  CI (99.9%): [2.941, 4.647] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.933 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.004 ms/op
Iteration   1: 3.950 ±(99.9%) 0.012 ms/op
Iteration   2: 3.933 ±(99.9%) 0.005 ms/op
Iteration   3: 3.814 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.899 ±(99.9%) 1.349 ms/op [Average]
  (min, avg, max) = (3.814, 3.899, 3.950), stdev = 0.074
  CI (99.9%): [2.550, 5.248] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.864 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.321 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.623 ±(99.9%) 0.012 ms/op
Iteration   1: 4.558 ±(99.9%) 0.012 ms/op
Iteration   2: 4.721 ±(99.9%) 0.008 ms/op
Iteration   3: 4.480 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.586 ±(99.9%) 2.246 ms/op [Average]
  (min, avg, max) = (4.480, 4.586, 4.721), stdev = 0.123
  CI (99.9%): [2.341, 6.832] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.570 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.159 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.016 ms/op
Iteration   1: 3.954 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  23.364 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.968 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  25.374 ms/op
                 createUser·p0.9999: 27.296 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 3.852 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  18.318 ms/op
                 createUser·p0.9999: 32.594 ms/op
                 createUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244428
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 352 
    [ 2.500,  5.000) = 233475 
    [ 5.000,  7.500) = 9176 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     23.270 ms/op
     p(99.9900) =     30.755 ms/op
     p(99.9990) =     33.078 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.498 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.012 ms/op
Iteration   1: 3.861 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   7.037 ms/op
                 existUser·p0.999:  10.014 ms/op
                 existUser·p0.9999: 28.195 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   2: 3.866 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.344 ms/op
                 existUser·p0.999:  25.269 ms/op
                 existUser·p0.9999: 27.572 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   3: 3.737 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.874 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.030 ms/op
                 existUser·p0.999:  14.713 ms/op
                 existUser·p0.9999: 30.507 ms/op
                 existUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251333
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 215 
    [ 2.500,  5.000) = 243211 
    [ 5.000,  7.500) = 6306 
    [ 7.500, 10.000) = 1196 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     29.880 ms/op
     p(99.9990) =     31.014 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.097 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.013 ms/op
Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   7.484 ms/op
                 getUser·p0.999:  17.727 ms/op
                 getUser·p0.9999: 27.587 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 3.904 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  26.740 ms/op
                 getUser·p0.9999: 29.603 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   3: 3.927 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.909 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  10.398 ms/op
                 getUser·p0.9999: 32.664 ms/op
                 getUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243984
  mean =      3.932 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 231468 
    [ 5.000,  7.500) = 10795 
    [ 7.500, 10.000) = 1176 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     31.575 ms/op
     p(99.9990) =     33.674 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.967 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.510 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.858 ±(99.9%) 0.017 ms/op
Iteration   1: 4.713 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  24.089 ms/op
                 listUser·p0.9999: 27.441 ms/op
                 listUser·p1.00:   28.246 ms/op

Iteration   2: 4.659 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   3: 4.799 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.532 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  17.028 ms/op
                 listUser·p0.9999: 27.383 ms/op
                 listUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203147
  mean =      4.723 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 174231 
    [ 5.000,  7.500) = 23488 
    [ 7.500, 10.000) = 4058 
    [10.000, 12.500) = 763 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 107 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      8.987 ms/op
     p(99.9000) =     20.705 ms/op
     p(99.9900) =     27.427 ms/op
     p(99.9990) =     28.239 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.037 ± 6.814  ops/ms
ClientPb.existUser                       thrpt       3   8.347 ± 3.719  ops/ms
ClientPb.getUser                         thrpt       3   8.190 ± 1.572  ops/ms
ClientPb.listUser                        thrpt       3   7.011 ± 2.770  ops/ms
ClientPb.createUser                       avgt       3   3.904 ± 0.631   ms/op
ClientPb.existUser                        avgt       3   3.794 ± 0.853   ms/op
ClientPb.getUser                          avgt       3   3.899 ± 1.349   ms/op
ClientPb.listUser                         avgt       3   4.586 ± 2.246   ms/op
ClientPb.createUser                     sample  244428   3.924 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.630           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.791           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.270           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.755           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.227           ms/op
ClientPb.existUser                      sample  251333   3.820 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.855           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.604           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.668           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.696           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.880           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.097           ms/op
ClientPb.getUser                        sample  243984   3.932 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.415           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.629           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.575           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.144           ms/op
ClientPb.listUser                       sample  203147   4.723 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.618           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.987           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.705           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.427           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.377           ms/op
