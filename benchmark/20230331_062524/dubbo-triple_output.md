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
# Warmup Iteration   1: 1.137 ops/ms
# Warmup Iteration   2: 2.444 ops/ms
# Warmup Iteration   3: 5.365 ops/ms
Iteration   1: 5.454 ops/ms
Iteration   2: 5.406 ops/ms
Iteration   3: 5.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.499 ±(99.9%) 2.254 ops/ms [Average]
  (min, avg, max) = (5.406, 5.499, 5.639), stdev = 0.124
  CI (99.9%): [3.246, 7.753] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.695 ops/ms
# Warmup Iteration   2: 5.038 ops/ms
# Warmup Iteration   3: 5.904 ops/ms
Iteration   1: 5.746 ops/ms
Iteration   2: 5.957 ops/ms
Iteration   3: 5.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.886 ±(99.9%) 2.203 ops/ms [Average]
  (min, avg, max) = (5.746, 5.886, 5.957), stdev = 0.121
  CI (99.9%): [3.682, 8.089] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.492 ops/ms
# Warmup Iteration   2: 4.286 ops/ms
# Warmup Iteration   3: 5.546 ops/ms
Iteration   1: 5.500 ops/ms
Iteration   2: 5.700 ops/ms
Iteration   3: 5.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.690 ±(99.9%) 3.370 ops/ms [Average]
  (min, avg, max) = (5.500, 5.690, 5.869), stdev = 0.185
  CI (99.9%): [2.320, 9.059] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.445 ops/ms
# Warmup Iteration   2: 3.728 ops/ms
# Warmup Iteration   3: 4.631 ops/ms
Iteration   1: 4.689 ops/ms
Iteration   2: 4.961 ops/ms
Iteration   3: 4.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.800 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (4.689, 4.800, 4.961), stdev = 0.143
  CI (99.9%): [2.196, 7.404] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.902 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.105 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.164 ±(99.9%) 0.010 ms/op
Iteration   1: 5.915 ±(99.9%) 0.017 ms/op
Iteration   2: 5.724 ±(99.9%) 0.011 ms/op
Iteration   3: 5.702 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.780 ±(99.9%) 2.143 ms/op [Average]
  (min, avg, max) = (5.702, 5.780, 5.915), stdev = 0.117
  CI (99.9%): [3.637, 7.924] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.675 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.687 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.719 ±(99.9%) 0.015 ms/op
Iteration   1: 5.467 ±(99.9%) 0.012 ms/op
Iteration   2: 5.255 ±(99.9%) 0.019 ms/op
Iteration   3: 5.692 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.471 ±(99.9%) 3.986 ms/op [Average]
  (min, avg, max) = (5.255, 5.471, 5.692), stdev = 0.218
  CI (99.9%): [1.486, 9.457] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.834 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.029 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.880 ±(99.9%) 0.007 ms/op
Iteration   1: 5.649 ±(99.9%) 0.015 ms/op
Iteration   2: 5.492 ±(99.9%) 0.012 ms/op
Iteration   3: 5.659 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.600 ±(99.9%) 1.713 ms/op [Average]
  (min, avg, max) = (5.492, 5.600, 5.659), stdev = 0.094
  CI (99.9%): [3.887, 7.312] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.782 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.633 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.794 ±(99.9%) 0.013 ms/op
Iteration   1: 6.549 ±(99.9%) 0.012 ms/op
Iteration   2: 6.645 ±(99.9%) 0.013 ms/op
Iteration   3: 6.115 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.437 ±(99.9%) 5.150 ms/op [Average]
  (min, avg, max) = (6.115, 6.437, 6.645), stdev = 0.282
  CI (99.9%): [1.286, 11.587] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.281 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.813 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.163 ±(99.9%) 0.027 ms/op
Iteration   1: 5.991 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.666 ms/op
                 createUser·p0.50:   5.710 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   11.440 ms/op
                 createUser·p0.999:  17.047 ms/op
                 createUser·p0.9999: 28.530 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   2: 5.720 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.601 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   6.906 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  25.989 ms/op
                 createUser·p0.9999: 29.753 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   3: 5.811 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.531 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.340 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  28.960 ms/op
                 createUser·p0.9999: 31.620 ms/op
                 createUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164382
  mean =      5.838 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 37403 
    [ 5.000,  7.500) = 113943 
    [ 7.500, 10.000) = 10229 
    [10.000, 12.500) = 1934 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.531 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.200 ms/op
     p(99.0000) =     11.111 ms/op
     p(99.9000) =     18.943 ms/op
     p(99.9900) =     30.919 ms/op
     p(99.9990) =     31.937 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.492 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.125 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.796 ±(99.9%) 0.023 ms/op
Iteration   1: 5.869 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.784 ms/op
                 existUser·p0.50:   5.513 ms/op
                 existUser·p0.90:   7.496 ms/op
                 existUser·p0.95:   8.618 ms/op
                 existUser·p0.99:   11.239 ms/op
                 existUser·p0.999:  20.283 ms/op
                 existUser·p0.9999: 26.731 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   2: 5.586 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.794 ms/op
                 existUser·p0.50:   5.292 ms/op
                 existUser·p0.90:   6.955 ms/op
                 existUser·p0.95:   7.845 ms/op
                 existUser·p0.99:   9.880 ms/op
                 existUser·p0.999:  27.493 ms/op
                 existUser·p0.9999: 33.201 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   3: 5.584 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.302 ms/op
                 existUser·p0.50:   5.292 ms/op
                 existUser·p0.90:   6.865 ms/op
                 existUser·p0.95:   7.864 ms/op
                 existUser·p0.99:   10.928 ms/op
                 existUser·p0.999:  16.544 ms/op
                 existUser·p0.9999: 35.211 ms/op
                 existUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168983
  mean =      5.676 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 50030 
    [ 5.000,  7.500) = 106054 
    [ 7.500, 10.000) = 10353 
    [10.000, 12.500) = 1727 
    [12.500, 15.000) = 453 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.094 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     18.777 ms/op
     p(99.9900) =     33.407 ms/op
     p(99.9990) =     36.359 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.506 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 7.641 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.981 ±(99.9%) 0.023 ms/op
Iteration   1: 5.913 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.548 ms/op
                 getUser·p0.50:   5.669 ms/op
                 getUser·p0.90:   7.004 ms/op
                 getUser·p0.95:   8.036 ms/op
                 getUser·p0.99:   11.600 ms/op
                 getUser·p0.999:  16.284 ms/op
                 getUser·p0.9999: 24.921 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 5.820 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   7.332 ms/op
                 getUser·p0.95:   8.503 ms/op
                 getUser·p0.99:   11.829 ms/op
                 getUser·p0.999:  24.314 ms/op
                 getUser·p0.9999: 27.365 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 5.832 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.855 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   7.990 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  27.072 ms/op
                 getUser·p0.9999: 30.427 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163833
  mean =      5.855 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 32591 
    [ 5.000,  7.500) = 118802 
    [ 7.500, 10.000) = 9405 
    [10.000, 12.500) = 2022 
    [12.500, 15.000) = 449 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      5.554 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     22.320 ms/op
     p(99.9900) =     29.479 ms/op
     p(99.9990) =     31.070 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 19.656 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 7.884 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.868 ±(99.9%) 0.027 ms/op
Iteration   1: 6.644 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   8.339 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  28.861 ms/op
                 listUser·p0.9999: 33.299 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   2: 6.685 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.510 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.020 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.894 ms/op
                 listUser·p0.999:  28.972 ms/op
                 listUser·p0.9999: 32.724 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   3: 6.687 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.256 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  27.492 ms/op
                 listUser·p0.9999: 33.583 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143799
  mean =      6.672 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 4008 
    [ 5.000,  7.500) = 117970 
    [ 7.500, 10.000) = 16773 
    [10.000, 12.500) = 3730 
    [12.500, 15.000) = 780 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 114 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.339 ms/op
     p(50.0000) =      6.332 ms/op
     p(90.0000) =      8.077 ms/op
     p(95.0000) =      9.339 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     28.416 ms/op
     p(99.9900) =     33.024 ms/op
     p(99.9990) =     36.831 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.499 ± 2.254  ops/ms
ClientPb.existUser                       thrpt       3   5.886 ± 2.203  ops/ms
ClientPb.getUser                         thrpt       3   5.690 ± 3.370  ops/ms
ClientPb.listUser                        thrpt       3   4.800 ± 2.604  ops/ms
ClientPb.createUser                       avgt       3   5.780 ± 2.143   ms/op
ClientPb.existUser                        avgt       3   5.471 ± 3.986   ms/op
ClientPb.getUser                          avgt       3   5.600 ± 1.713   ms/op
ClientPb.listUser                         avgt       3   6.437 ± 5.150   ms/op
ClientPb.createUser                     sample  164382   5.838 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.200           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.111           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.943           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.919           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.211           ms/op
ClientPb.existUser                      sample  168983   5.676 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.784           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.094           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.135           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.777           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.407           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.766           ms/op
ClientPb.getUser                        sample  163833   5.855 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.967           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.258           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.567           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.320           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.479           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  143799   6.672 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.339           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.332           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.077           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.339           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.288           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.416           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.024           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.831           ms/op
