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
# Warmup Iteration   1: 1.605 ops/ms
# Warmup Iteration   2: 3.235 ops/ms
# Warmup Iteration   3: 7.096 ops/ms
Iteration   1: 7.698 ops/ms
Iteration   2: 7.699 ops/ms
Iteration   3: 7.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.639 ±(99.9%) 1.884 ops/ms [Average]
  (min, avg, max) = (7.520, 7.639, 7.699), stdev = 0.103
  CI (99.9%): [5.755, 9.522] (assumes normal distribution)


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
# Warmup Iteration   1: 2.598 ops/ms
# Warmup Iteration   2: 6.792 ops/ms
# Warmup Iteration   3: 8.154 ops/ms
Iteration   1: 8.545 ops/ms
Iteration   2: 8.420 ops/ms
Iteration   3: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.442 ±(99.9%) 1.719 ops/ms [Average]
  (min, avg, max) = (8.360, 8.442, 8.545), stdev = 0.094
  CI (99.9%): [6.723, 10.161] (assumes normal distribution)


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
# Warmup Iteration   1: 2.164 ops/ms
# Warmup Iteration   2: 6.612 ops/ms
# Warmup Iteration   3: 7.224 ops/ms
Iteration   1: 7.540 ops/ms
Iteration   2: 8.125 ops/ms
Iteration   3: 8.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.962 ±(99.9%) 6.715 ops/ms [Average]
  (min, avg, max) = (7.540, 7.962, 8.220), stdev = 0.368
  CI (99.9%): [1.246, 14.677] (assumes normal distribution)


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
# Warmup Iteration   1: 2.271 ops/ms
# Warmup Iteration   2: 5.985 ops/ms
# Warmup Iteration   3: 6.765 ops/ms
Iteration   1: 7.025 ops/ms
Iteration   2: 6.969 ops/ms
Iteration   3: 7.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.037 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (6.969, 7.037, 7.115), stdev = 0.074
  CI (99.9%): [5.694, 8.379] (assumes normal distribution)


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
# Warmup Iteration   1: 14.047 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.620 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.006 ms/op
Iteration   1: 3.955 ±(99.9%) 0.004 ms/op
Iteration   2: 3.943 ±(99.9%) 0.009 ms/op
Iteration   3: 3.720 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.873 ±(99.9%) 2.415 ms/op [Average]
  (min, avg, max) = (3.720, 3.873, 3.955), stdev = 0.132
  CI (99.9%): [1.458, 6.287] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.797 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.009 ms/op
Iteration   1: 3.832 ±(99.9%) 0.008 ms/op
Iteration   2: 3.789 ±(99.9%) 0.007 ms/op
Iteration   3: 3.797 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.806 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (3.789, 3.806, 3.832), stdev = 0.023
  CI (99.9%): [3.389, 4.223] (assumes normal distribution)


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
# Warmup Iteration   1: 12.923 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.820 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.005 ms/op
Iteration   1: 4.141 ±(99.9%) 0.005 ms/op
Iteration   2: 3.926 ±(99.9%) 0.008 ms/op
Iteration   3: 3.969 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.012 ±(99.9%) 2.069 ms/op [Average]
  (min, avg, max) = (3.926, 4.012, 4.141), stdev = 0.113
  CI (99.9%): [1.943, 6.081] (assumes normal distribution)


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
# Warmup Iteration   1: 14.013 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.094 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.928 ±(99.9%) 0.006 ms/op
Iteration   1: 4.846 ±(99.9%) 0.009 ms/op
Iteration   2: 4.643 ±(99.9%) 0.010 ms/op
Iteration   3: 5.083 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.857 ±(99.9%) 4.016 ms/op [Average]
  (min, avg, max) = (4.643, 4.857, 5.083), stdev = 0.220
  CI (99.9%): [0.841, 8.873] (assumes normal distribution)


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
# Warmup Iteration   1: 12.409 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.346 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.544 ±(99.9%) 0.019 ms/op
Iteration   1: 3.993 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  22.998 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 3.901 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.962 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  10.420 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 4.139 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   8.818 ms/op
                 createUser·p0.999:  26.154 ms/op
                 createUser·p0.9999: 30.614 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239412
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 356 
    [ 2.500,  5.000) = 224981 
    [ 5.000,  7.500) = 11447 
    [ 7.500, 10.000) = 1841 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     22.990 ms/op
     p(99.9900) =     28.838 ms/op
     p(99.9990) =     31.455 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 13.422 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.516 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.011 ms/op
Iteration   1: 4.080 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  20.709 ms/op
                 existUser·p0.9999: 28.523 ms/op
                 existUser·p1.00:   29.983 ms/op

Iteration   2: 3.806 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 25.166 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   3: 3.934 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  16.625 ms/op
                 existUser·p0.9999: 27.853 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244017
  mean =      3.937 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 526 
    [ 2.500,  5.000) = 227669 
    [ 5.000,  7.500) = 13753 
    [ 7.500, 10.000) = 1352 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     16.506 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     29.870 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 13.062 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 4.791 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.011 ms/op
Iteration   1: 4.249 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  24.240 ms/op
                 getUser·p0.9999: 26.273 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 3.932 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  14.044 ms/op
                 getUser·p0.9999: 29.735 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   3: 3.944 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  28.082 ms/op
                 getUser·p0.9999: 31.574 ms/op
                 getUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237767
  mean =      4.037 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 225615 
    [ 5.000,  7.500) = 9145 
    [ 7.500, 10.000) = 1944 
    [10.000, 12.500) = 549 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     30.514 ms/op
     p(99.9990) =     32.190 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 14.673 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.863 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.020 ms/op
Iteration   1: 4.757 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  25.844 ms/op
                 listUser·p0.9999: 29.387 ms/op
                 listUser·p1.00:   30.999 ms/op

Iteration   2: 4.920 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  21.823 ms/op
                 listUser·p0.9999: 28.393 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   3: 4.618 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  17.656 ms/op
                 listUser·p0.9999: 19.898 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201565
  mean =      4.762 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 164321 
    [ 5.000,  7.500) = 30938 
    [ 7.500, 10.000) = 4958 
    [10.000, 12.500) = 710 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.958 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.423 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     21.571 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     30.431 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.639 ± 1.884  ops/ms
ClientPb.existUser                       thrpt       3   8.442 ± 1.719  ops/ms
ClientPb.getUser                         thrpt       3   7.962 ± 6.715  ops/ms
ClientPb.listUser                        thrpt       3   7.037 ± 1.342  ops/ms
ClientPb.createUser                       avgt       3   3.873 ± 2.415   ms/op
ClientPb.existUser                        avgt       3   3.806 ± 0.417   ms/op
ClientPb.getUser                          avgt       3   4.012 ± 2.069   ms/op
ClientPb.listUser                         avgt       3   4.857 ± 4.016   ms/op
ClientPb.createUser                     sample  239412   4.009 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.386           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.651           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.990           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.838           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.014           ms/op
ClientPb.existUser                      sample  244017   3.937 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.581           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.307           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.506           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.951           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.983           ms/op
ClientPb.getUser                        sample  237767   4.037 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.446           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.216           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.514           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  201565   4.762 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.958           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.423           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.571           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.410           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.999           ms/op
