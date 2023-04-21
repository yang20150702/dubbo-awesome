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
# Warmup Iteration   1: 1.670 ops/ms
# Warmup Iteration   2: 3.314 ops/ms
# Warmup Iteration   3: 7.159 ops/ms
Iteration   1: 7.499 ops/ms
Iteration   2: 8.185 ops/ms
Iteration   3: 8.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.953 ±(99.9%) 7.172 ops/ms [Average]
  (min, avg, max) = (7.499, 7.953, 8.185), stdev = 0.393
  CI (99.9%): [0.780, 15.125] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.227 ops/ms
# Warmup Iteration   2: 7.648 ops/ms
# Warmup Iteration   3: 7.804 ops/ms
Iteration   1: 8.090 ops/ms
Iteration   2: 8.372 ops/ms
Iteration   3: 8.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.331 ±(99.9%) 4.070 ops/ms [Average]
  (min, avg, max) = (8.090, 8.331, 8.531), stdev = 0.223
  CI (99.9%): [4.261, 12.401] (assumes normal distribution)


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
# Warmup Iteration   1: 2.207 ops/ms
# Warmup Iteration   2: 6.655 ops/ms
# Warmup Iteration   3: 7.717 ops/ms
Iteration   1: 7.836 ops/ms
Iteration   2: 7.655 ops/ms
Iteration   3: 8.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.888 ±(99.9%) 4.786 ops/ms [Average]
  (min, avg, max) = (7.655, 7.888, 8.172), stdev = 0.262
  CI (99.9%): [3.102, 12.674] (assumes normal distribution)


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
# Warmup Iteration   1: 1.942 ops/ms
# Warmup Iteration   2: 5.620 ops/ms
# Warmup Iteration   3: 6.835 ops/ms
Iteration   1: 6.689 ops/ms
Iteration   2: 6.755 ops/ms
Iteration   3: 6.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.788 ±(99.9%) 2.166 ops/ms [Average]
  (min, avg, max) = (6.689, 6.788, 6.920), stdev = 0.119
  CI (99.9%): [4.622, 8.954] (assumes normal distribution)


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
# Warmup Iteration   1: 12.306 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.010 ms/op
Iteration   1: 3.875 ±(99.9%) 0.009 ms/op
Iteration   2: 3.820 ±(99.9%) 0.008 ms/op
Iteration   3: 3.930 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.875 ±(99.9%) 1.006 ms/op [Average]
  (min, avg, max) = (3.820, 3.875, 3.930), stdev = 0.055
  CI (99.9%): [2.869, 4.881] (assumes normal distribution)


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
# Warmup Iteration   1: 12.606 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.009 ms/op
Iteration   1: 3.772 ±(99.9%) 0.008 ms/op
Iteration   2: 3.968 ±(99.9%) 0.010 ms/op
Iteration   3: 3.923 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.888 ±(99.9%) 1.870 ms/op [Average]
  (min, avg, max) = (3.772, 3.888, 3.968), stdev = 0.103
  CI (99.9%): [2.018, 5.758] (assumes normal distribution)


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
# Warmup Iteration   1: 12.324 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.006 ms/op
Iteration   1: 4.004 ±(99.9%) 0.009 ms/op
Iteration   2: 3.891 ±(99.9%) 0.007 ms/op
Iteration   3: 3.966 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.953 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (3.891, 3.953, 4.004), stdev = 0.057
  CI (99.9%): [2.905, 5.002] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.313 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.395 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.808 ±(99.9%) 0.009 ms/op
Iteration   1: 4.589 ±(99.9%) 0.016 ms/op
Iteration   2: 4.440 ±(99.9%) 0.016 ms/op
Iteration   3: 4.726 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.585 ±(99.9%) 2.604 ms/op [Average]
  (min, avg, max) = (4.440, 4.585, 4.726), stdev = 0.143
  CI (99.9%): [1.982, 7.189] (assumes normal distribution)


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
# Warmup Iteration   1: 13.257 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.367 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.018 ms/op
Iteration   1: 4.197 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  10.879 ms/op
                 createUser·p0.9999: 25.309 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.930 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  25.220 ms/op
                 createUser·p0.9999: 28.438 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 3.927 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  16.082 ms/op
                 createUser·p0.9999: 50.453 ms/op
                 createUser·p1.00:   51.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238981
  mean =      4.014 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 224646 
    [ 5.000, 10.000) = 13735 
    [10.000, 15.000) = 342 
    [15.000, 20.000) = 34 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 136 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 20 
    [50.000, 55.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     16.139 ms/op
     p(99.9900) =     48.713 ms/op
     p(99.9990) =     50.987 ms/op
     p(99.9999) =     51.446 ms/op
    p(100.0000) =     51.446 ms/op


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
# Warmup Iteration   1: 12.217 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.011 ms/op
Iteration   1: 3.761 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.077 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.680 ms/op
                 existUser·p0.999:  22.839 ms/op
                 existUser·p0.9999: 25.002 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.978 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   7.774 ms/op
                 existUser·p0.999:  13.903 ms/op
                 existUser·p0.9999: 27.165 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.918 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  21.004 ms/op
                 existUser·p0.9999: 30.731 ms/op
                 existUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247072
  mean =      3.884 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 175 
    [ 2.500,  5.000) = 235218 
    [ 5.000,  7.500) = 9472 
    [ 7.500, 10.000) = 1722 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     29.108 ms/op
     p(99.9990) =     31.369 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 12.875 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.855 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
Iteration   1: 4.257 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   6.373 ms/op
                 getUser·p0.99:   9.175 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 26.689 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   2: 4.042 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.007 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.979 ms/op
                 getUser·p0.999:  27.197 ms/op
                 getUser·p0.9999: 35.775 ms/op
                 getUser·p1.00:   39.191 ms/op

Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 31.064 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235490
  mean =      4.075 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 222272 
    [ 5.000,  7.500) = 9551 
    [ 7.500, 10.000) = 2538 
    [10.000, 12.500) = 529 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     24.642 ms/op
     p(99.9900) =     33.971 ms/op
     p(99.9990) =     38.246 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 14.587 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 6.287 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.064 ±(99.9%) 0.020 ms/op
Iteration   1: 4.811 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  26.457 ms/op
                 listUser·p0.9999: 28.475 ms/op
                 listUser·p1.00:   29.393 ms/op

Iteration   2: 4.653 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  20.880 ms/op
                 listUser·p0.9999: 25.366 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   3: 4.700 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203447
  mean =      4.720 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 168742 
    [ 5.000,  7.500) = 29655 
    [ 7.500, 10.000) = 3860 
    [10.000, 12.500) = 618 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     28.212 ms/op
     p(99.9990) =     29.121 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.953 ± 7.172  ops/ms
ClientPb.existUser                       thrpt       3   8.331 ± 4.070  ops/ms
ClientPb.getUser                         thrpt       3   7.888 ± 4.786  ops/ms
ClientPb.listUser                        thrpt       3   6.788 ± 2.166  ops/ms
ClientPb.createUser                       avgt       3   3.875 ± 1.006   ms/op
ClientPb.existUser                        avgt       3   3.888 ± 1.870   ms/op
ClientPb.getUser                          avgt       3   3.953 ± 1.049   ms/op
ClientPb.listUser                         avgt       3   4.585 ± 2.604   ms/op
ClientPb.createUser                     sample  238981   4.014 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.640           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.128           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.160           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.139           ms/op
ClientPb.createUser:createUser·p0.9999  sample          48.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          51.446           ms/op
ClientPb.existUser                      sample  247072   3.884 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.509           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.948           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.972           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.108           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.621           ms/op
ClientPb.getUser                        sample  235490   4.075 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.401           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.315           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.642           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.971           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.191           ms/op
ClientPb.listUser                       sample  203447   4.720 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.154           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.931           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.037           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.212           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.393           ms/op
