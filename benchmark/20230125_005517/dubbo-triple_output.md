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
# Warmup Iteration   1: 2.234 ops/ms
# Warmup Iteration   2: 6.003 ops/ms
# Warmup Iteration   3: 8.381 ops/ms
Iteration   1: 9.154 ops/ms
Iteration   2: 9.443 ops/ms
Iteration   3: 9.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.285 ±(99.9%) 2.667 ops/ms [Average]
  (min, avg, max) = (9.154, 9.285, 9.443), stdev = 0.146
  CI (99.9%): [6.618, 11.952] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.933 ops/ms
# Warmup Iteration   2: 8.627 ops/ms
# Warmup Iteration   3: 9.636 ops/ms
Iteration   1: 9.554 ops/ms
Iteration   2: 9.971 ops/ms
Iteration   3: 9.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.693 ±(99.9%) 4.394 ops/ms [Average]
  (min, avg, max) = (9.554, 9.693, 9.971), stdev = 0.241
  CI (99.9%): [5.300, 14.087] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.205 ops/ms
# Warmup Iteration   2: 8.566 ops/ms
# Warmup Iteration   3: 8.789 ops/ms
Iteration   1: 8.983 ops/ms
Iteration   2: 8.899 ops/ms
Iteration   3: 9.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.965 ±(99.9%) 1.069 ops/ms [Average]
  (min, avg, max) = (8.899, 8.965, 9.012), stdev = 0.059
  CI (99.9%): [7.896, 10.034] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.840 ops/ms
# Warmup Iteration   2: 7.063 ops/ms
# Warmup Iteration   3: 7.844 ops/ms
Iteration   1: 8.162 ops/ms
Iteration   2: 8.038 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.153 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (8.038, 8.153, 8.259), stdev = 0.111
  CI (99.9%): [6.133, 10.174] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.756 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.007 ms/op
Iteration   1: 3.325 ±(99.9%) 0.010 ms/op
Iteration   2: 3.403 ±(99.9%) 0.006 ms/op
Iteration   3: 3.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.419 ±(99.9%) 1.885 ms/op [Average]
  (min, avg, max) = (3.325, 3.419, 3.529), stdev = 0.103
  CI (99.9%): [1.534, 5.304] (assumes normal distribution)


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
# Warmup Iteration   1: 7.809 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.006 ms/op
Iteration   1: 3.200 ±(99.9%) 0.005 ms/op
Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
Iteration   3: 3.320 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.239 ±(99.9%) 1.276 ms/op [Average]
  (min, avg, max) = (3.197, 3.239, 3.320), stdev = 0.070
  CI (99.9%): [1.963, 4.515] (assumes normal distribution)


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
# Warmup Iteration   1: 7.865 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.006 ms/op
Iteration   1: 3.480 ±(99.9%) 0.005 ms/op
Iteration   2: 3.367 ±(99.9%) 0.008 ms/op
Iteration   3: 3.338 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.395 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.338, 3.395, 3.480), stdev = 0.075
  CI (99.9%): [2.023, 4.767] (assumes normal distribution)


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
# Warmup Iteration   1: 10.430 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.009 ms/op
Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
Iteration   2: 4.022 ±(99.9%) 0.012 ms/op
Iteration   3: 3.984 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.978 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.928, 3.978, 4.022), stdev = 0.047
  CI (99.9%): [3.122, 4.834] (assumes normal distribution)


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
# Warmup Iteration   1: 8.838 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.012 ms/op
Iteration   1: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  21.103 ms/op
                 createUser·p0.9999: 24.499 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  22.938 ms/op
                 createUser·p0.9999: 30.368 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  19.065 ms/op
                 createUser·p0.9999: 24.693 ms/op
                 createUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277444
  mean =      3.457 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7020 
    [ 2.500,  5.000) = 264411 
    [ 5.000,  7.500) = 4797 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 155 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     28.811 ms/op
     p(99.9990) =     31.097 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.277 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.009 ms/op
Iteration   1: 3.254 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.273 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 22.501 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   3: 3.362 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  21.213 ms/op
                 existUser·p0.9999: 32.259 ms/op
                 existUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291126
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12131 
    [ 2.500,  5.000) = 273216 
    [ 5.000,  7.500) = 4718 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     13.056 ms/op
     p(99.9900) =     30.369 ms/op
     p(99.9990) =     32.517 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.207 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
Iteration   1: 3.388 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   6.026 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.972 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.590 ms/op
                 getUser·p0.999:  23.915 ms/op
                 getUser·p0.9999: 26.234 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  18.662 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280069
  mean =      3.426 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4676 
    [ 2.500,  5.000) = 268223 
    [ 5.000,  7.500) = 5916 
    [ 7.500, 10.000) = 722 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 102 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     18.807 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     28.751 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.283 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.014 ms/op
Iteration   1: 4.158 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  22.020 ms/op
                 listUser·p0.9999: 24.920 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 4.092 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   3: 3.877 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.050 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.251 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.499 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237586
  mean =      4.039 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 227416 
    [ 5.000,  7.500) = 7185 
    [ 7.500, 10.000) = 1930 
    [10.000, 12.500) = 399 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     17.847 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     25.563 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.285 ± 2.667  ops/ms
ClientPb.existUser                       thrpt       3   9.693 ± 4.394  ops/ms
ClientPb.getUser                         thrpt       3   8.965 ± 1.069  ops/ms
ClientPb.listUser                        thrpt       3   8.153 ± 2.020  ops/ms
ClientPb.createUser                       avgt       3   3.419 ± 1.885   ms/op
ClientPb.existUser                        avgt       3   3.239 ± 1.276   ms/op
ClientPb.getUser                          avgt       3   3.395 ± 1.372   ms/op
ClientPb.listUser                         avgt       3   3.978 ± 0.856   ms/op
ClientPb.createUser                     sample  277444   3.457 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.937           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.054           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.811           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.097           ms/op
ClientPb.existUser                      sample  291126   3.296 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.851           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.056           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  280069   3.426 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.628           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.807           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.066           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  237586   4.039 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.497           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.847           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.855           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
