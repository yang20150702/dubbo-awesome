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
# Warmup Iteration   1: 1.584 ops/ms
# Warmup Iteration   2: 3.666 ops/ms
# Warmup Iteration   3: 7.064 ops/ms
Iteration   1: 7.566 ops/ms
Iteration   2: 7.995 ops/ms
Iteration   3: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.873 ±(99.9%) 4.877 ops/ms [Average]
  (min, avg, max) = (7.566, 7.873, 8.057), stdev = 0.267
  CI (99.9%): [2.996, 12.750] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.350 ops/ms
# Warmup Iteration   2: 7.385 ops/ms
# Warmup Iteration   3: 8.114 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.415 ops/ms
Iteration   3: 7.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.148 ±(99.9%) 6.702 ops/ms [Average]
  (min, avg, max) = (7.729, 8.148, 8.415), stdev = 0.367
  CI (99.9%): [1.446, 14.850] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.045 ops/ms
# Warmup Iteration   2: 6.471 ops/ms
# Warmup Iteration   3: 7.400 ops/ms
Iteration   1: 8.020 ops/ms
Iteration   2: 7.823 ops/ms
Iteration   3: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.975 ±(99.9%) 2.466 ops/ms [Average]
  (min, avg, max) = (7.823, 7.975, 8.082), stdev = 0.135
  CI (99.9%): [5.509, 10.441] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.026 ops/ms
# Warmup Iteration   2: 5.820 ops/ms
# Warmup Iteration   3: 6.502 ops/ms
Iteration   1: 6.740 ops/ms
Iteration   2: 6.884 ops/ms
Iteration   3: 6.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.793 ±(99.9%) 1.434 ops/ms [Average]
  (min, avg, max) = (6.740, 6.793, 6.884), stdev = 0.079
  CI (99.9%): [5.359, 8.227] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.814 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.484 ±(99.9%) 0.007 ms/op
Iteration   1: 4.051 ±(99.9%) 0.012 ms/op
Iteration   2: 3.961 ±(99.9%) 0.010 ms/op
Iteration   3: 3.985 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.999 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.961, 3.999, 4.051), stdev = 0.047
  CI (99.9%): [3.146, 4.852] (assumes normal distribution)


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
# Warmup Iteration   1: 12.342 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.005 ms/op
Iteration   1: 4.013 ±(99.9%) 0.005 ms/op
Iteration   2: 3.778 ±(99.9%) 0.011 ms/op
Iteration   3: 3.761 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.851 ±(99.9%) 2.574 ms/op [Average]
  (min, avg, max) = (3.761, 3.851, 4.013), stdev = 0.141
  CI (99.9%): [1.277, 6.425] (assumes normal distribution)


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
# Warmup Iteration   1: 14.137 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.289 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.004 ms/op
Iteration   1: 3.948 ±(99.9%) 0.008 ms/op
Iteration   2: 4.315 ±(99.9%) 0.005 ms/op
Iteration   3: 4.216 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.160 ±(99.9%) 3.457 ms/op [Average]
  (min, avg, max) = (3.948, 4.160, 4.315), stdev = 0.190
  CI (99.9%): [0.702, 7.617] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.609 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.928 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.010 ±(99.9%) 0.006 ms/op
Iteration   1: 4.778 ±(99.9%) 0.008 ms/op
Iteration   2: 4.702 ±(99.9%) 0.011 ms/op
Iteration   3: 4.796 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.759 ±(99.9%) 0.902 ms/op [Average]
  (min, avg, max) = (4.702, 4.759, 4.796), stdev = 0.049
  CI (99.9%): [3.856, 5.661] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.007 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 6.075 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 4.544 ±(99.9%) 0.020 ms/op
Iteration   1: 4.048 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  15.188 ms/op
                 createUser·p0.9999: 25.955 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   2: 4.144 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  28.058 ms/op
                 createUser·p0.9999: 33.498 ms/op
                 createUser·p1.00:   34.275 ms/op

Iteration   3: 4.200 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   7.844 ms/op
                 createUser·p0.999:  25.395 ms/op
                 createUser·p0.9999: 31.961 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232484
  mean =      4.130 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 401 
    [ 2.500,  5.000) = 213714 
    [ 5.000,  7.500) = 16103 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     23.496 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     33.926 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 11.366 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.012 ms/op
Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   7.291 ms/op
                 existUser·p0.999:  11.668 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   2: 4.019 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.880 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   7.242 ms/op
                 existUser·p0.999:  10.596 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.944 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.817 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   7.242 ms/op
                 existUser·p0.999:  28.148 ms/op
                 existUser·p0.9999: 42.584 ms/op
                 existUser·p1.00:   43.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241623
  mean =      3.972 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 229590 
    [ 5.000, 10.000) = 11464 
    [10.000, 15.000) = 325 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 137 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.642 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.264 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     41.146 ms/op
     p(99.9990) =     43.369 ms/op
     p(99.9999) =     43.516 ms/op
    p(100.0000) =     43.516 ms/op


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
# Warmup Iteration   1: 13.137 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.995 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.483 ±(99.9%) 0.017 ms/op
Iteration   1: 4.084 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   8.241 ms/op
                 getUser·p0.999:  24.117 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 3.964 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  12.987 ms/op
                 getUser·p0.9999: 27.886 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 4.186 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  27.480 ms/op
                 getUser·p0.9999: 31.174 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235475
  mean =      4.076 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 220722 
    [ 5.000,  7.500) = 11974 
    [ 7.500, 10.000) = 1722 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 121 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     24.184 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     31.359 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 13.797 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.600 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.824 ±(99.9%) 0.017 ms/op
Iteration   1: 4.816 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  28.458 ms/op
                 listUser·p0.9999: 31.392 ms/op
                 listUser·p1.00:   32.276 ms/op

Iteration   2: 4.798 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.634 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.210 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  19.218 ms/op
                 listUser·p0.9999: 23.136 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 4.724 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  18.555 ms/op
                 listUser·p0.9999: 21.591 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200876
  mean =      4.779 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 165367 
    [ 5.000,  7.500) = 30012 
    [ 7.500, 10.000) = 4012 
    [10.000, 12.500) = 739 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     30.406 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.873 ± 4.877  ops/ms
ClientPb.existUser                       thrpt       3   8.148 ± 6.702  ops/ms
ClientPb.getUser                         thrpt       3   7.975 ± 2.466  ops/ms
ClientPb.listUser                        thrpt       3   6.793 ± 1.434  ops/ms
ClientPb.createUser                       avgt       3   3.999 ± 0.853   ms/op
ClientPb.existUser                        avgt       3   3.851 ± 2.574   ms/op
ClientPb.getUser                          avgt       3   4.160 ± 3.457   ms/op
ClientPb.listUser                         avgt       3   4.759 ± 0.902   ms/op
ClientPb.createUser                     sample  232484   4.130 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.458           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.447           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.496           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.047           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  241623   3.972 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.642           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.264           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.054           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.146           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.516           ms/op
ClientPb.getUser                        sample  235475   4.076 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.399           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.308           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.184           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.409           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.392           ms/op
ClientPb.listUser                       sample  200876   4.779 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.355           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.103           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.406           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.276           ms/op
