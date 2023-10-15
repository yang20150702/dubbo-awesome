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
# Warmup Iteration   1: 1.856 ops/ms
# Warmup Iteration   2: 3.543 ops/ms
# Warmup Iteration   3: 7.344 ops/ms
Iteration   1: 7.738 ops/ms
Iteration   2: 8.298 ops/ms
Iteration   3: 8.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.137 ±(99.9%) 6.345 ops/ms [Average]
  (min, avg, max) = (7.738, 8.137, 8.375), stdev = 0.348
  CI (99.9%): [1.791, 14.482] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.290 ops/ms
# Warmup Iteration   2: 7.469 ops/ms
# Warmup Iteration   3: 8.286 ops/ms
Iteration   1: 8.438 ops/ms
Iteration   2: 8.510 ops/ms
Iteration   3: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.430 ±(99.9%) 1.534 ops/ms [Average]
  (min, avg, max) = (8.343, 8.430, 8.510), stdev = 0.084
  CI (99.9%): [6.897, 9.964] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.248 ops/ms
# Warmup Iteration   2: 6.584 ops/ms
# Warmup Iteration   3: 8.013 ops/ms
Iteration   1: 7.843 ops/ms
Iteration   2: 7.601 ops/ms
Iteration   3: 8.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.980 ±(99.9%) 8.421 ops/ms [Average]
  (min, avg, max) = (7.601, 7.980, 8.494), stdev = 0.462
  CI (99.9%): [≈ 0, 16.400] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 5.714 ops/ms
# Warmup Iteration   3: 6.748 ops/ms
Iteration   1: 6.831 ops/ms
Iteration   2: 7.073 ops/ms
Iteration   3: 7.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.056 ±(99.9%) 3.975 ops/ms [Average]
  (min, avg, max) = (6.831, 7.056, 7.266), stdev = 0.218
  CI (99.9%): [3.081, 11.031] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.745 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.005 ms/op
Iteration   1: 4.116 ±(99.9%) 0.004 ms/op
Iteration   2: 3.786 ±(99.9%) 0.005 ms/op
Iteration   3: 3.844 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.915 ±(99.9%) 3.215 ms/op [Average]
  (min, avg, max) = (3.786, 3.915, 4.116), stdev = 0.176
  CI (99.9%): [0.700, 7.130] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.536 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.004 ms/op
Iteration   1: 3.626 ±(99.9%) 0.004 ms/op
Iteration   2: 3.605 ±(99.9%) 0.004 ms/op
Iteration   3: 3.575 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.602 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.575, 3.602, 3.626), stdev = 0.026
  CI (99.9%): [3.131, 4.072] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.995 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.005 ms/op
Iteration   1: 3.784 ±(99.9%) 0.007 ms/op
Iteration   2: 3.870 ±(99.9%) 0.004 ms/op
Iteration   3: 3.829 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.828 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.784, 3.828, 3.870), stdev = 0.043
  CI (99.9%): [3.046, 4.610] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.960 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.950 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.756 ±(99.9%) 0.009 ms/op
Iteration   1: 4.576 ±(99.9%) 0.006 ms/op
Iteration   2: 4.699 ±(99.9%) 0.006 ms/op
Iteration   3: 4.828 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.701 ±(99.9%) 2.299 ms/op [Average]
  (min, avg, max) = (4.576, 4.701, 4.828), stdev = 0.126
  CI (99.9%): [2.402, 7.000] (assumes normal distribution)


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
# Warmup Iteration   1: 13.576 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.863 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.017 ms/op
Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   8.364 ms/op
                 createUser·p0.999:  10.957 ms/op
                 createUser·p0.9999: 25.080 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   2: 4.033 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  22.503 ms/op
                 createUser·p0.9999: 25.234 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   3: 4.057 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  24.412 ms/op
                 createUser·p0.9999: 29.471 ms/op
                 createUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236058
  mean =      4.064 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 373 
    [ 2.500,  5.000) = 223552 
    [ 5.000,  7.500) = 9968 
    [ 7.500, 10.000) = 1470 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     21.822 ms/op
     p(99.9900) =     28.055 ms/op
     p(99.9990) =     30.221 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 11.639 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
Iteration   1: 3.866 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.767 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  22.610 ms/op
                 existUser·p0.9999: 25.199 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 3.906 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.230 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 26.051 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.954 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.479 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   8.053 ms/op
                 existUser·p0.999:  14.157 ms/op
                 existUser·p0.9999: 31.022 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245597
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 428 
    [ 2.500,  5.000) = 234650 
    [ 5.000,  7.500) = 8447 
    [ 7.500, 10.000) = 1332 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     29.112 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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
# Warmup Iteration   1: 12.337 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.011 ms/op
Iteration   1: 3.955 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  23.172 ms/op
                 getUser·p0.9999: 25.949 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   2: 3.923 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  15.135 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   3: 3.982 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  26.187 ms/op
                 getUser·p0.9999: 29.392 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242646
  mean =      3.953 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 143 
    [ 2.500,  5.000) = 234121 
    [ 5.000,  7.500) = 6478 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 112 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.025 ms/op
     p(99.9000) =     23.059 ms/op
     p(99.9900) =     28.598 ms/op
     p(99.9990) =     29.889 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 14.858 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.806 ±(99.9%) 0.015 ms/op
Iteration   1: 4.708 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  23.399 ms/op
                 listUser·p0.9999: 26.171 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   2: 4.737 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.068 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 21.700 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 4.807 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.996 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  17.972 ms/op
                 listUser·p0.9999: 20.810 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202046
  mean =      4.750 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 161949 
    [ 5.000,  7.500) = 35018 
    [ 7.500, 10.000) = 3861 
    [10.000, 12.500) = 452 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     26.670 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.137 ± 6.345  ops/ms
ClientPb.existUser                       thrpt       3   8.430 ± 1.534  ops/ms
ClientPb.getUser                         thrpt       3   7.980 ± 8.421  ops/ms
ClientPb.listUser                        thrpt       3   7.056 ± 3.975  ops/ms
ClientPb.createUser                       avgt       3   3.915 ± 3.215   ms/op
ClientPb.existUser                        avgt       3   3.602 ± 0.470   ms/op
ClientPb.getUser                          avgt       3   3.828 ± 0.782   ms/op
ClientPb.listUser                         avgt       3   4.701 ± 2.299   ms/op
ClientPb.createUser                     sample  236058   4.064 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.348           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.055           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.376           ms/op
ClientPb.existUser                      sample  245597   3.908 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.479           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.448           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.882           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.112           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.818           ms/op
ClientPb.getUser                        sample  242646   3.953 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.954           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.025           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.059           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.598           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.950           ms/op
ClientPb.listUser                       sample  202046   4.750 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.526           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.103           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.661           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.395           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.787           ms/op
