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
# Warmup Iteration   1: 1.155 ops/ms
# Warmup Iteration   2: 2.672 ops/ms
# Warmup Iteration   3: 5.797 ops/ms
Iteration   1: 5.828 ops/ms
Iteration   2: 5.966 ops/ms
Iteration   3: 5.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.852 ±(99.9%) 1.903 ops/ms [Average]
  (min, avg, max) = (5.762, 5.852, 5.966), stdev = 0.104
  CI (99.9%): [3.949, 7.755] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.756 ops/ms
# Warmup Iteration   2: 4.447 ops/ms
# Warmup Iteration   3: 6.511 ops/ms
Iteration   1: 5.950 ops/ms
Iteration   2: 6.399 ops/ms
Iteration   3: 6.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.248 ±(99.9%) 4.705 ops/ms [Average]
  (min, avg, max) = (5.950, 6.248, 6.399), stdev = 0.258
  CI (99.9%): [1.543, 10.953] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.597 ops/ms
# Warmup Iteration   2: 4.618 ops/ms
# Warmup Iteration   3: 5.883 ops/ms
Iteration   1: 5.888 ops/ms
Iteration   2: 5.941 ops/ms
Iteration   3: 6.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.948 ±(99.9%) 1.154 ops/ms [Average]
  (min, avg, max) = (5.888, 5.948, 6.014), stdev = 0.063
  CI (99.9%): [4.794, 7.102] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.735 ops/ms
# Warmup Iteration   2: 3.816 ops/ms
# Warmup Iteration   3: 5.013 ops/ms
Iteration   1: 4.889 ops/ms
Iteration   2: 5.154 ops/ms
Iteration   3: 5.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.031 ±(99.9%) 2.439 ops/ms [Average]
  (min, avg, max) = (4.889, 5.031, 5.154), stdev = 0.134
  CI (99.9%): [2.592, 7.469] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 18.813 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.676 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.724 ±(99.9%) 0.009 ms/op
Iteration   1: 5.419 ±(99.9%) 0.013 ms/op
Iteration   2: 5.522 ±(99.9%) 0.016 ms/op
Iteration   3: 5.316 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.419 ±(99.9%) 1.877 ms/op [Average]
  (min, avg, max) = (5.316, 5.419, 5.522), stdev = 0.103
  CI (99.9%): [3.542, 7.296] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.745 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.684 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.296 ±(99.9%) 0.006 ms/op
Iteration   1: 5.147 ±(99.9%) 0.013 ms/op
Iteration   2: 5.192 ±(99.9%) 0.008 ms/op
Iteration   3: 4.954 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.097 ±(99.9%) 2.309 ms/op [Average]
  (min, avg, max) = (4.954, 5.097, 5.192), stdev = 0.127
  CI (99.9%): [2.788, 7.406] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.731 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.478 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.205 ±(99.9%) 0.011 ms/op
Iteration   1: 5.473 ±(99.9%) 0.011 ms/op
Iteration   2: 5.365 ±(99.9%) 0.012 ms/op
Iteration   3: 5.429 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.422 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (5.365, 5.422, 5.473), stdev = 0.054
  CI (99.9%): [4.432, 6.413] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 17.168 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 7.100 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.306 ±(99.9%) 0.010 ms/op
Iteration   1: 5.915 ±(99.9%) 0.015 ms/op
Iteration   2: 6.080 ±(99.9%) 0.018 ms/op
Iteration   3: 6.068 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.021 ±(99.9%) 1.674 ms/op [Average]
  (min, avg, max) = (5.915, 6.021, 6.080), stdev = 0.092
  CI (99.9%): [4.347, 7.695] (assumes normal distribution)


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
# Warmup Iteration   1: 17.707 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.485 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.717 ±(99.9%) 0.025 ms/op
Iteration   1: 5.388 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.191 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.340 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 26.251 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   2: 5.244 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.552 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.299 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  25.242 ms/op
                 createUser·p0.9999: 32.276 ms/op
                 createUser·p1.00:   35.979 ms/op

Iteration   3: 5.244 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   4.874 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.389 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  25.931 ms/op
                 createUser·p0.9999: 29.335 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181295
  mean =      5.291 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 92925 
    [ 5.000,  7.500) = 80392 
    [ 7.500, 10.000) = 6307 
    [10.000, 12.500) = 1069 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     31.792 ms/op
     p(99.9990) =     35.660 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 16.754 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 5.663 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.449 ±(99.9%) 0.020 ms/op
Iteration   1: 5.037 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.212 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   6.865 ms/op
                 existUser·p0.99:   9.339 ms/op
                 existUser·p0.999:  21.874 ms/op
                 existUser·p0.9999: 25.886 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 5.129 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   7.152 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  23.645 ms/op
                 existUser·p0.9999: 28.249 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   3: 5.122 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.367 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.431 ms/op
                 existUser·p0.95:   7.283 ms/op
                 existUser·p0.99:   9.460 ms/op
                 existUser·p0.999:  26.890 ms/op
                 existUser·p0.9999: 31.285 ms/op
                 existUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188335
  mean =      5.096 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 111828 
    [ 5.000,  7.500) = 69544 
    [ 7.500, 10.000) = 5498 
    [10.000, 12.500) = 1037 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.111 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     21.998 ms/op
     p(99.9900) =     30.469 ms/op
     p(99.9990) =     32.301 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 16.955 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.230 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.615 ±(99.9%) 0.022 ms/op
Iteration   1: 5.543 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.642 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.914 ms/op
                 getUser·p0.95:   8.323 ms/op
                 getUser·p0.99:   13.091 ms/op
                 getUser·p0.999:  23.233 ms/op
                 getUser·p0.9999: 30.185 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   2: 5.345 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   4.997 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   10.273 ms/op
                 getUser·p0.999:  23.729 ms/op
                 getUser·p0.9999: 29.952 ms/op
                 getUser·p1.00:   32.309 ms/op

Iteration   3: 5.315 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.605 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  28.393 ms/op
                 getUser·p0.9999: 31.383 ms/op
                 getUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177762
  mean =      5.399 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 88415 
    [ 5.000,  7.500) = 78523 
    [ 7.500, 10.000) = 8163 
    [10.000, 12.500) = 1508 
    [12.500, 15.000) = 712 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.807 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     23.502 ms/op
     p(99.9900) =     30.784 ms/op
     p(99.9990) =     32.233 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 17.933 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 6.969 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.192 ±(99.9%) 0.023 ms/op
Iteration   1: 6.220 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.550 ms/op
                 listUser·p0.999:  28.345 ms/op
                 listUser·p0.9999: 31.944 ms/op
                 listUser·p1.00:   33.391 ms/op

Iteration   2: 6.079 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   10.974 ms/op
                 listUser·p0.999:  27.191 ms/op
                 listUser·p0.9999: 32.134 ms/op
                 listUser·p1.00:   33.522 ms/op

Iteration   3: 6.232 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.953 ms/op
                 listUser·p0.999:  23.541 ms/op
                 listUser·p0.9999: 34.954 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155384
  mean =      6.177 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 12499 
    [ 5.000,  7.500) = 127729 
    [ 7.500, 10.000) = 11574 
    [10.000, 12.500) = 2368 
    [12.500, 15.000) = 600 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.837 ms/op
     p(50.0000) =      5.825 ms/op
     p(90.0000) =      7.471 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     11.813 ms/op
     p(99.9000) =     27.467 ms/op
     p(99.9900) =     33.191 ms/op
     p(99.9990) =     35.733 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.852 ± 1.903  ops/ms
ClientPb.existUser                       thrpt       3   6.248 ± 4.705  ops/ms
ClientPb.getUser                         thrpt       3   5.948 ± 1.154  ops/ms
ClientPb.listUser                        thrpt       3   5.031 ± 2.439  ops/ms
ClientPb.createUser                       avgt       3   5.419 ± 1.877   ms/op
ClientPb.existUser                        avgt       3   5.097 ± 2.309   ms/op
ClientPb.getUser                          avgt       3   5.422 ± 0.990   ms/op
ClientPb.listUser                         avgt       3   6.021 ± 1.674   ms/op
ClientPb.createUser                     sample  181295   5.291 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.968           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.562           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.340           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.863           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.053           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.792           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  188335   5.096 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.715           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.111           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.470           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.998           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.469           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.735           ms/op
ClientPb.getUser                        sample  177762   5.399 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.046           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.807           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.010           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.502           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.784           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.309           ms/op
ClientPb.listUser                       sample  155384   6.177 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.837           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.825           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.667           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.813           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.467           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.191           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.241           ms/op
