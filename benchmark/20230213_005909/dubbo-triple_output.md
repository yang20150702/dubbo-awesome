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
# Warmup Iteration   1: 1.022 ops/ms
# Warmup Iteration   2: 2.284 ops/ms
# Warmup Iteration   3: 4.903 ops/ms
Iteration   1: 5.653 ops/ms
Iteration   2: 5.826 ops/ms
Iteration   3: 5.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.693 ±(99.9%) 2.145 ops/ms [Average]
  (min, avg, max) = (5.601, 5.693, 5.826), stdev = 0.118
  CI (99.9%): [3.548, 7.839] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.597 ops/ms
# Warmup Iteration   2: 4.831 ops/ms
# Warmup Iteration   3: 5.874 ops/ms
Iteration   1: 6.177 ops/ms
Iteration   2: 6.269 ops/ms
Iteration   3: 6.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.152 ±(99.9%) 2.412 ops/ms [Average]
  (min, avg, max) = (6.009, 6.152, 6.269), stdev = 0.132
  CI (99.9%): [3.740, 8.564] (assumes normal distribution)


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
# Warmup Iteration   1: 1.517 ops/ms
# Warmup Iteration   2: 4.289 ops/ms
# Warmup Iteration   3: 5.707 ops/ms
Iteration   1: 5.533 ops/ms
Iteration   2: 5.236 ops/ms
Iteration   3: 5.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.477 ±(99.9%) 3.990 ops/ms [Average]
  (min, avg, max) = (5.236, 5.477, 5.663), stdev = 0.219
  CI (99.9%): [1.487, 9.467] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.492 ops/ms
# Warmup Iteration   2: 3.681 ops/ms
# Warmup Iteration   3: 4.787 ops/ms
Iteration   1: 4.992 ops/ms
Iteration   2: 4.992 ops/ms
Iteration   3: 4.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.925 ±(99.9%) 2.099 ops/ms [Average]
  (min, avg, max) = (4.793, 4.925, 4.992), stdev = 0.115
  CI (99.9%): [2.827, 7.024] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 16.438 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.909 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.003 ±(99.9%) 0.013 ms/op
Iteration   1: 5.550 ±(99.9%) 0.015 ms/op
Iteration   2: 5.641 ±(99.9%) 0.015 ms/op
Iteration   3: 5.597 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.596 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (5.550, 5.596, 5.641), stdev = 0.046
  CI (99.9%): [4.765, 6.426] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 19.942 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.878 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.770 ±(99.9%) 0.010 ms/op
Iteration   1: 5.432 ±(99.9%) 0.008 ms/op
Iteration   2: 5.513 ±(99.9%) 0.012 ms/op
Iteration   3: 5.619 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.522 ±(99.9%) 1.709 ms/op [Average]
  (min, avg, max) = (5.432, 5.522, 5.619), stdev = 0.094
  CI (99.9%): [3.812, 7.231] (assumes normal distribution)


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
# Warmup Iteration   1: 18.802 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.774 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.049 ±(99.9%) 0.009 ms/op
Iteration   1: 5.737 ±(99.9%) 0.009 ms/op
Iteration   2: 5.708 ±(99.9%) 0.009 ms/op
Iteration   3: 5.719 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.721 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (5.708, 5.721, 5.737), stdev = 0.015
  CI (99.9%): [5.452, 5.991] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.786 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 9.266 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.743 ±(99.9%) 0.014 ms/op
Iteration   1: 6.964 ±(99.9%) 0.010 ms/op
Iteration   2: 6.754 ±(99.9%) 0.017 ms/op
Iteration   3: 6.564 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.761 ±(99.9%) 3.643 ms/op [Average]
  (min, avg, max) = (6.564, 6.761, 6.964), stdev = 0.200
  CI (99.9%): [3.118, 10.403] (assumes normal distribution)


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
# Warmup Iteration   1: 19.275 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 8.230 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.559 ±(99.9%) 0.034 ms/op
Iteration   1: 5.921 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.470 ms/op
                 createUser·p0.50:   5.661 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   11.977 ms/op
                 createUser·p0.999:  16.450 ms/op
                 createUser·p0.9999: 29.681 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   2: 5.711 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.556 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   6.849 ms/op
                 createUser·p0.95:   7.619 ms/op
                 createUser·p0.99:   9.945 ms/op
                 createUser·p0.999:  27.664 ms/op
                 createUser·p0.9999: 32.716 ms/op
                 createUser·p1.00:   33.423 ms/op

Iteration   3: 5.672 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.717 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  28.637 ms/op
                 createUser·p0.9999: 31.588 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166298
  mean =      5.766 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 38649 
    [ 5.000,  7.500) = 116874 
    [ 7.500, 10.000) = 8044 
    [10.000, 12.500) = 1851 
    [12.500, 15.000) = 522 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     24.609 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     33.336 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 17.158 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.886 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.582 ±(99.9%) 0.021 ms/op
Iteration   1: 5.485 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.118 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.808 ms/op
                 existUser·p0.95:   8.249 ms/op
                 existUser·p0.99:   11.354 ms/op
                 existUser·p0.999:  23.779 ms/op
                 existUser·p0.9999: 30.365 ms/op
                 existUser·p1.00:   31.228 ms/op

Iteration   2: 5.271 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.062 ms/op
                 existUser·p0.95:   6.922 ms/op
                 existUser·p0.99:   11.017 ms/op
                 existUser·p0.999:  25.362 ms/op
                 existUser·p0.9999: 28.312 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 5.324 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.575 ms/op
                 existUser·p0.99:   11.232 ms/op
                 existUser·p0.999:  18.940 ms/op
                 existUser·p0.9999: 27.099 ms/op
                 existUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179036
  mean =      5.358 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 82930 
    [ 5.000,  7.500) = 86607 
    [ 7.500, 10.000) = 6419 
    [10.000, 12.500) = 1872 
    [12.500, 15.000) = 670 
    [15.000, 17.500) = 295 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     19.394 ms/op
     p(99.9900) =     28.321 ms/op
     p(99.9990) =     31.202 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 19.474 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.960 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.024 ms/op
Iteration   1: 5.871 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.683 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.455 ms/op
                 getUser·p0.95:   8.782 ms/op
                 getUser·p0.99:   11.895 ms/op
                 getUser·p0.999:  16.704 ms/op
                 getUser·p0.9999: 30.791 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   2: 5.698 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.822 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   6.887 ms/op
                 getUser·p0.95:   8.298 ms/op
                 getUser·p0.99:   11.715 ms/op
                 getUser·p0.999:  27.842 ms/op
                 getUser·p0.9999: 31.470 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   3: 5.665 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.879 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   6.840 ms/op
                 getUser·p0.95:   7.848 ms/op
                 getUser·p0.99:   10.535 ms/op
                 getUser·p0.999:  29.032 ms/op
                 getUser·p0.9999: 31.982 ms/op
                 getUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167054
  mean =      5.743 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 40880 
    [ 5.000,  7.500) = 113304 
    [ 7.500, 10.000) = 9750 
    [10.000, 12.500) = 2130 
    [12.500, 15.000) = 652 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 82 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.683 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.045 ms/op
     p(95.0000) =      8.380 ms/op
     p(99.0000) =     11.542 ms/op
     p(99.9000) =     21.070 ms/op
     p(99.9900) =     31.532 ms/op
     p(99.9990) =     32.090 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 19.071 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.944 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.835 ±(99.9%) 0.029 ms/op
Iteration   1: 6.920 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.982 ms/op
                 listUser·p0.50:   6.382 ms/op
                 listUser·p0.90:   9.159 ms/op
                 listUser·p0.95:   10.682 ms/op
                 listUser·p0.99:   13.582 ms/op
                 listUser·p0.999:  29.904 ms/op
                 listUser·p0.9999: 33.907 ms/op
                 listUser·p1.00:   34.669 ms/op

Iteration   2: 6.860 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   6.337 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.174 ms/op
                 listUser·p0.99:   13.500 ms/op
                 listUser·p0.999:  32.473 ms/op
                 listUser·p0.9999: 34.013 ms/op
                 listUser·p1.00:   35.324 ms/op

Iteration   3: 6.524 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   7.897 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   12.255 ms/op
                 listUser·p0.999:  29.489 ms/op
                 listUser·p0.9999: 35.021 ms/op
                 listUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141861
  mean =      6.763 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 3236 
    [ 5.000,  7.500) = 113263 
    [ 7.500, 10.000) = 17603 
    [10.000, 12.500) = 5795 
    [12.500, 15.000) = 1237 
    [15.000, 17.500) = 339 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 88 
    [32.500, 35.000) = 84 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.257 ms/op
     p(50.0000) =      6.259 ms/op
     p(90.0000) =      8.700 ms/op
     p(95.0000) =     10.158 ms/op
     p(99.0000) =     13.304 ms/op
     p(99.9000) =     30.736 ms/op
     p(99.9900) =     34.067 ms/op
     p(99.9990) =     36.001 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.693 ± 2.145  ops/ms
ClientPb.existUser                       thrpt       3   6.152 ± 2.412  ops/ms
ClientPb.getUser                         thrpt       3   5.477 ± 3.990  ops/ms
ClientPb.listUser                        thrpt       3   4.925 ± 2.099  ops/ms
ClientPb.createUser                       avgt       3   5.596 ± 0.830   ms/op
ClientPb.existUser                        avgt       3   5.522 ± 1.709   ms/op
ClientPb.getUser                          avgt       3   5.721 ± 0.270   ms/op
ClientPb.listUser                         avgt       3   6.761 ± 3.643   ms/op
ClientPb.createUser                     sample  166298   5.766 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.335           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.930           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.905           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.141           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.609           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.588           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.423           ms/op
ClientPb.existUser                      sample  179036   5.358 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.251           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.046           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.619           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.239           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.394           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.321           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.228           ms/op
ClientPb.getUser                        sample  167054   5.743 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.407           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.045           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.380           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.542           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.070           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.532           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.244           ms/op
ClientPb.listUser                       sample  141861   6.763 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.257           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.259           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.700           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.158           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.304           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.736           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.067           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.110           ms/op
