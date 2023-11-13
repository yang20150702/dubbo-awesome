# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.221 ops/ms
# Warmup Iteration   2: 5.600 ops/ms
# Warmup Iteration   3: 8.853 ops/ms
Iteration   1: 9.623 ops/ms
Iteration   2: 9.838 ops/ms
Iteration   3: 9.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.717 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (9.623, 9.717, 9.838), stdev = 0.110
  CI (99.9%): [7.707, 11.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.301 ops/ms
# Warmup Iteration   2: 8.870 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 10.400 ops/ms
Iteration   2: 10.025 ops/ms
Iteration   3: 10.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.196 ±(99.9%) 3.453 ops/ms [Average]
  (min, avg, max) = (10.025, 10.196, 10.400), stdev = 0.189
  CI (99.9%): [6.744, 13.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ops/ms
# Warmup Iteration   2: 8.690 ops/ms
# Warmup Iteration   3: 9.722 ops/ms
Iteration   1: 10.049 ops/ms
Iteration   2: 9.997 ops/ms
Iteration   3: 9.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.002 ±(99.9%) 0.808 ops/ms [Average]
  (min, avg, max) = (9.960, 10.002, 10.049), stdev = 0.044
  CI (99.9%): [9.194, 10.810] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.962 ops/ms
# Warmup Iteration   2: 7.264 ops/ms
# Warmup Iteration   3: 8.085 ops/ms
Iteration   1: 8.339 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.383 ±(99.9%) 0.966 ops/ms [Average]
  (min, avg, max) = (8.339, 8.383, 8.441), stdev = 0.053
  CI (99.9%): [7.416, 9.349] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.375 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.001 ms/op
Iteration   1: 3.340 ±(99.9%) 0.004 ms/op
Iteration   2: 3.271 ±(99.9%) 0.004 ms/op
Iteration   3: 3.280 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.297 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.271, 3.297, 3.340), stdev = 0.037
  CI (99.9%): [2.614, 3.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.087 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.002 ms/op
Iteration   1: 3.137 ±(99.9%) 0.005 ms/op
Iteration   2: 3.119 ±(99.9%) 0.004 ms/op
Iteration   3: 3.146 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.134 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (3.119, 3.134, 3.146), stdev = 0.014
  CI (99.9%): [2.878, 3.390] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.877 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.003 ms/op
Iteration   1: 3.315 ±(99.9%) 0.003 ms/op
Iteration   2: 3.264 ±(99.9%) 0.003 ms/op
Iteration   3: 3.308 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.296 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.264, 3.296, 3.315), stdev = 0.028
  CI (99.9%): [2.787, 3.804] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.400 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.005 ms/op
Iteration   1: 3.825 ±(99.9%) 0.003 ms/op
Iteration   2: 3.795 ±(99.9%) 0.009 ms/op
Iteration   3: 3.828 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.816 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (3.795, 3.816, 3.828), stdev = 0.018
  CI (99.9%): [3.481, 4.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.782 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
Iteration   1: 3.269 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  14.633 ms/op
                 createUser·p0.9999: 21.549 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  15.818 ms/op
                 createUser·p0.9999: 24.394 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 3.312 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  17.933 ms/op
                 createUser·p0.9999: 22.992 ms/op
                 createUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292328
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12296 
    [ 2.500,  5.000) = 275741 
    [ 5.000,  7.500) = 3254 
    [ 7.500, 10.000) = 527 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     16.657 ms/op
     p(99.9900) =     23.482 ms/op
     p(99.9990) =     24.820 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.647 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
Iteration   1: 3.214 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  8.807 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.195 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  18.128 ms/op
                 existUser·p0.9999: 30.466 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 21.556 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301215
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12033 
    [ 2.500,  5.000) = 283554 
    [ 5.000,  7.500) = 4930 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     16.151 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     32.211 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.011 ms/op
Iteration   1: 3.337 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  17.673 ms/op
                 getUser·p0.9999: 20.939 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  8.142 ms/op
                 getUser·p0.9999: 22.622 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.249 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  16.841 ms/op
                 getUser·p0.9999: 24.119 ms/op
                 getUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291190
  mean =      3.295 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7336 
    [ 2.500,  5.000) = 278330 
    [ 5.000,  7.500) = 4586 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.249 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     16.670 ms/op
     p(99.9900) =     22.733 ms/op
     p(99.9990) =     25.469 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.143 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
Iteration   1: 3.914 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 19.196 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 3.852 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.024 ms/op
                 listUser·p0.999:  12.732 ms/op
                 listUser·p0.9999: 18.869 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 3.938 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.291 ms/op
                 listUser·p0.999:  12.546 ms/op
                 listUser·p0.9999: 13.932 ms/op
                 listUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245987
  mean =      3.901 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 239838 
    [ 5.000,  7.500) = 4697 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     18.789 ms/op
     p(99.9990) =     20.825 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.717 ± 2.009  ops/ms
ClientPb.existUser                       thrpt       3  10.196 ± 3.453  ops/ms
ClientPb.getUser                         thrpt       3  10.002 ± 0.808  ops/ms
ClientPb.listUser                        thrpt       3   8.383 ± 0.966  ops/ms
ClientPb.createUser                       avgt       3   3.297 ± 0.684   ms/op
ClientPb.existUser                        avgt       3   3.134 ± 0.256   ms/op
ClientPb.getUser                          avgt       3   3.296 ± 0.509   ms/op
ClientPb.listUser                         avgt       3   3.816 ± 0.335   ms/op
ClientPb.createUser                     sample  292328   3.283 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.323           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.657           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.482           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.100           ms/op
ClientPb.existUser                      sample  301215   3.185 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.151           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.462           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  291190   3.295 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.249           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.670           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.733           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.625           ms/op
ClientPb.listUser                       sample  245987   3.901 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.403           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.713           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.789           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.037           ms/op
