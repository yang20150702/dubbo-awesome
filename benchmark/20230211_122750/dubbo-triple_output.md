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
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 6.370 ops/ms
# Warmup Iteration   3: 8.786 ops/ms
Iteration   1: 9.262 ops/ms
Iteration   2: 9.287 ops/ms
Iteration   3: 9.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.422 ±(99.9%) 4.670 ops/ms [Average]
  (min, avg, max) = (9.262, 9.422, 9.718), stdev = 0.256
  CI (99.9%): [4.752, 14.092] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.016 ops/ms
# Warmup Iteration   2: 8.848 ops/ms
# Warmup Iteration   3: 9.576 ops/ms
Iteration   1: 10.061 ops/ms
Iteration   2: 10.186 ops/ms
Iteration   3: 9.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.977 ±(99.9%) 4.763 ops/ms [Average]
  (min, avg, max) = (9.684, 9.977, 10.186), stdev = 0.261
  CI (99.9%): [5.214, 14.740] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 8.546 ops/ms
# Warmup Iteration   3: 9.655 ops/ms
Iteration   1: 9.860 ops/ms
Iteration   2: 9.743 ops/ms
Iteration   3: 9.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.712 ±(99.9%) 3.027 ops/ms [Average]
  (min, avg, max) = (9.533, 9.712, 9.860), stdev = 0.166
  CI (99.9%): [6.685, 12.739] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.959 ops/ms
# Warmup Iteration   2: 7.417 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 8.026 ops/ms
Iteration   2: 8.201 ops/ms
Iteration   3: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.112 ±(99.9%) 1.594 ops/ms [Average]
  (min, avg, max) = (8.026, 8.112, 8.201), stdev = 0.087
  CI (99.9%): [6.518, 9.705] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.136 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.007 ms/op
Iteration   1: 3.325 ±(99.9%) 0.009 ms/op
Iteration   2: 3.404 ±(99.9%) 0.006 ms/op
Iteration   3: 3.255 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.328 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (3.255, 3.328, 3.404), stdev = 0.075
  CI (99.9%): [1.967, 4.688] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.363 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.003 ms/op
Iteration   1: 3.128 ±(99.9%) 0.007 ms/op
Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
Iteration   3: 3.258 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.178 ±(99.9%) 1.277 ms/op [Average]
  (min, avg, max) = (3.128, 3.178, 3.258), stdev = 0.070
  CI (99.9%): [1.902, 4.455] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.730 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.004 ms/op
Iteration   1: 3.375 ±(99.9%) 0.003 ms/op
Iteration   2: 3.396 ±(99.9%) 0.006 ms/op
Iteration   3: 3.316 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.363 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.316, 3.363, 3.396), stdev = 0.041
  CI (99.9%): [2.608, 4.118] (assumes normal distribution)


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
# Warmup Iteration   1: 10.134 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.007 ms/op
Iteration   1: 3.886 ±(99.9%) 0.012 ms/op
Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
Iteration   3: 3.864 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.902 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.864, 3.902, 3.957), stdev = 0.049
  CI (99.9%): [3.015, 4.789] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.177 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.009 ms/op
Iteration   1: 3.525 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  10.174 ms/op
                 createUser·p0.9999: 29.816 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  21.862 ms/op
                 createUser·p0.9999: 26.963 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   6.565 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 23.252 ms/op
                 createUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280673
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13047 
    [ 2.500,  5.000) = 257758 
    [ 5.000,  7.500) = 8669 
    [ 7.500, 10.000) = 771 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.932 ms/op
     p(99.9900) =     28.567 ms/op
     p(99.9990) =     30.382 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 8.598 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
Iteration   1: 3.296 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.620 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  13.812 ms/op
                 existUser·p0.9999: 24.750 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 3.217 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  16.012 ms/op
                 existUser·p0.9999: 23.560 ms/op
                 existUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294666
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14537 
    [ 2.500,  5.000) = 275024 
    [ 5.000,  7.500) = 4094 
    [ 7.500, 10.000) = 579 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 150 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.282 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 9.750 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.011 ms/op
Iteration   1: 3.507 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  19.643 ms/op
                 getUser·p0.9999: 22.587 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   2: 3.343 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  21.638 ms/op
                 getUser·p0.9999: 25.016 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  19.719 ms/op
                 getUser·p0.9999: 26.898 ms/op
                 getUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282459
  mean =      3.396 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8407 
    [ 2.500,  5.000) = 266680 
    [ 5.000,  7.500) = 6203 
    [ 7.500, 10.000) = 680 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.565 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 10.569 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  19.920 ms/op
                 listUser·p0.9999: 24.277 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   2: 3.835 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.952 ms/op
                 listUser·p0.9999: 23.756 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 3.825 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.365 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 20.992 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245265
  mean =      3.911 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 238730 
    [ 5.000,  7.500) = 4428 
    [ 7.500, 10.000) = 1116 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.422 ± 4.670  ops/ms
ClientPb.existUser                       thrpt       3   9.977 ± 4.763  ops/ms
ClientPb.getUser                         thrpt       3   9.712 ± 3.027  ops/ms
ClientPb.listUser                        thrpt       3   8.112 ± 1.594  ops/ms
ClientPb.createUser                       avgt       3   3.328 ± 1.360   ms/op
ClientPb.existUser                        avgt       3   3.178 ± 1.277   ms/op
ClientPb.getUser                          avgt       3   3.363 ± 0.755   ms/op
ClientPb.listUser                         avgt       3   3.902 ± 0.887   ms/op
ClientPb.createUser                     sample  280673   3.420 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.151           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.932           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.567           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.638           ms/op
ClientPb.existUser                      sample  294666   3.256 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.593           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.821           ms/op
ClientPb.getUser                        sample  282459   3.396 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.885           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.661           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.182           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.853           ms/op
ClientPb.listUser                       sample  245265   3.911 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.236           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.724           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.985           ms/op
