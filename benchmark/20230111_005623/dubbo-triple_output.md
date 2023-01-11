# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.788 ops/ms
# Warmup Iteration   2: 3.758 ops/ms
# Warmup Iteration   3: 7.362 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 7.900 ops/ms
Iteration   3: 8.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.906 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (7.791, 7.906, 8.027), stdev = 0.118
  CI (99.9%): [5.753, 10.058] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.254 ops/ms
# Warmup Iteration   2: 6.697 ops/ms
# Warmup Iteration   3: 8.196 ops/ms
Iteration   1: 8.582 ops/ms
Iteration   2: 8.325 ops/ms
Iteration   3: 8.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.458 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (8.325, 8.458, 8.582), stdev = 0.129
  CI (99.9%): [6.109, 10.806] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 6.462 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.155 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.284 ±(99.9%) 4.381 ops/ms [Average]
  (min, avg, max) = (8.137, 8.284, 8.561), stdev = 0.240
  CI (99.9%): [3.903, 12.665] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.166 ops/ms
# Warmup Iteration   2: 5.953 ops/ms
# Warmup Iteration   3: 6.590 ops/ms
Iteration   1: 6.584 ops/ms
Iteration   2: 7.269 ops/ms
Iteration   3: 7.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.992 ±(99.9%) 6.590 ops/ms [Average]
  (min, avg, max) = (6.584, 6.992, 7.269), stdev = 0.361
  CI (99.9%): [0.403, 13.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.558 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.006 ms/op
Iteration   1: 4.023 ±(99.9%) 0.007 ms/op
Iteration   2: 3.932 ±(99.9%) 0.012 ms/op
Iteration   3: 3.749 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.901 ±(99.9%) 2.545 ms/op [Average]
  (min, avg, max) = (3.749, 3.901, 4.023), stdev = 0.139
  CI (99.9%): [1.357, 6.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.467 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.009 ms/op
Iteration   1: 3.842 ±(99.9%) 0.006 ms/op
Iteration   2: 3.861 ±(99.9%) 0.008 ms/op
Iteration   3: 3.674 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.792 ±(99.9%) 1.878 ms/op [Average]
  (min, avg, max) = (3.674, 3.792, 3.861), stdev = 0.103
  CI (99.9%): [1.914, 5.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.699 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.589 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.010 ms/op
Iteration   1: 3.977 ±(99.9%) 0.006 ms/op
Iteration   2: 3.915 ±(99.9%) 0.005 ms/op
Iteration   3: 3.923 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.938 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.915, 3.938, 3.977), stdev = 0.034
  CI (99.9%): [3.323, 4.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.684 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.390 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.771 ±(99.9%) 0.007 ms/op
Iteration   1: 4.732 ±(99.9%) 0.010 ms/op
Iteration   2: 4.820 ±(99.9%) 0.015 ms/op
Iteration   3: 4.735 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.763 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (4.732, 4.763, 4.820), stdev = 0.050
  CI (99.9%): [3.848, 5.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.313 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.110 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.399 ±(99.9%) 0.017 ms/op
Iteration   1: 4.010 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.815 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   7.889 ms/op
                 createUser·p0.999:  23.448 ms/op
                 createUser·p0.9999: 26.509 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 3.741 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  14.287 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 3.949 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  27.427 ms/op
                 createUser·p0.9999: 29.815 ms/op
                 createUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246339
  mean =      3.897 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 552 
    [ 2.500,  5.000) = 233464 
    [ 5.000,  7.500) = 10240 
    [ 7.500, 10.000) = 1344 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     23.320 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     30.298 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.859 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.013 ms/op
Iteration   1: 3.887 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   2: 3.758 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.796 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  25.029 ms/op
                 existUser·p0.9999: 27.836 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.812 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  19.045 ms/op
                 existUser·p0.9999: 31.637 ms/op
                 existUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251119
  mean =      3.818 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 771 
    [ 2.500,  5.000) = 239315 
    [ 5.000,  7.500) = 9152 
    [ 7.500, 10.000) = 1259 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     30.467 ms/op
     p(99.9990) =     32.517 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.356 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.707 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.012 ms/op
Iteration   1: 4.394 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.988 ms/op
                 getUser·p0.99:   9.535 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 34.406 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   2: 4.128 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.907 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  23.406 ms/op
                 getUser·p0.9999: 29.196 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 3.787 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.954 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  11.379 ms/op
                 getUser·p0.9999: 26.560 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234959
  mean =      4.088 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 207 
    [ 2.500,  5.000) = 213053 
    [ 5.000,  7.500) = 17712 
    [ 7.500, 10.000) = 2996 
    [10.000, 12.500) = 496 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     29.246 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.856 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.435 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.791 ±(99.9%) 0.018 ms/op
Iteration   1: 4.705 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.476 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  23.759 ms/op
                 listUser·p0.9999: 26.818 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 4.939 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.668 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  18.087 ms/op
                 listUser·p0.9999: 21.499 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 4.690 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   8.786 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 17.871 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200874
  mean =      4.775 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 166498 
    [ 5.000,  7.500) = 28666 
    [ 7.500, 10.000) = 4606 
    [10.000, 12.500) = 569 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     27.524 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.906 ± 2.152  ops/ms
ClientPb.existUser                       thrpt       3   8.458 ± 2.349  ops/ms
ClientPb.getUser                         thrpt       3   8.284 ± 4.381  ops/ms
ClientPb.listUser                        thrpt       3   6.992 ± 6.590  ops/ms
ClientPb.createUser                       avgt       3   3.901 ± 2.545   ms/op
ClientPb.existUser                        avgt       3   3.792 ± 1.878   ms/op
ClientPb.getUser                          avgt       3   3.938 ± 0.615   ms/op
ClientPb.listUser                         avgt       3   4.763 ± 0.915   ms/op
ClientPb.createUser                     sample  246339   3.897 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.169           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.320           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.228           ms/op
ClientPb.existUser                      sample  251119   3.818 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.421           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.612           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.467           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  234959   4.088 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.888           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.249           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.627           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.246           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  200874   4.775 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.476           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.210           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.990           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.395           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.623           ms/op
